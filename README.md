# Sinchon ICPC Camp ERD

> Generated by [`prisma-markdown`](https://github.com/samchon/prisma-markdown)

- [User](#user)
- [Grade](#grade)
- [Store](#store)
- [FavoriteStore](#favoritestore)
- [Product](#product)
- [Category](#category)
- [Stock](#stock)
- [Size](#size)
- [Inquiry](#inquiry)
- [Reply](#reply)
- [Review](#review)
- [Cart](#cart)
- [CartItem](#cartitem)
- [Order](#order)
- [OrderItem](#orderitem)
- [Payment](#payment)
- [Alarm](#alarm)
- [default](#default)

## User

```mermaid
erDiagram
"User" {
  String id PK
  String name
  String email UK
  String password
  String refreshToken "nullable"
  UserType type
  Int points
  DateTime createdAt
  DateTime updatedAt
  String gradeId FK
  String image "nullable"
}
"SalesLog" {
  String id PK
  String productId FK "nullable"
  String userId FK "nullable"
  String storeId FK "nullable"
  Int price
  Int quantity
  DateTime soldAt
}
"SalesLog" }o--o| "User" : buyer
```

### `User`

유저 모델입니다.

Properties as follows:

- `id`:
- `name`:
- `email`:
- `password`:
- `refreshToken`:
- `type`: enum인 UserType 을 통해 BUYER와 SELLER 를 구분합니다.
- `points`:
- `createdAt`:
- `updatedAt`:
- `gradeId`:
- `image`:

### `SalesLog`

판매 기록 통게 모델입니다.

Properties as follows:

- `id`:
- `productId`:
- `userId`:
- `storeId`:
- `price`:
- `quantity`:
- `soldAt`:

## Grade

```mermaid
erDiagram
"Grade" {
  String name
  String id PK
  Int rate
  Int minAmount
}
```

### `Grade`

등급 모델입니다.

Properties as follows:

- `name`:
- `id`:
- `rate`: 할인율
- `minAmount`: 달성 최소 금액

## Store

```mermaid
erDiagram
"Store" {
  String id PK
  String name
  DateTime createdAt
  DateTime updatedAt
  String userId FK,UK
  String address
  String phoneNumber
  String content
  String image
}
```

### `Store`

스토어 모델입니다.

Properties as follows:

- `id`:
- `name`:
- `createdAt`:
- `updatedAt`:
- `userId`:
- `address`:
- `phoneNumber`:
- `content`:
- `image`:

## FavoriteStore

```mermaid
erDiagram
"FavoriteStore" {
  String storeId FK
  String userId FK
}
```

### `FavoriteStore`

관심 스토어 모델입니다.

Properties as follows:

- `storeId`:
- `userId`:

## Product

```mermaid
erDiagram
"Product" {
  String id PK
  String name
  String image
  DateTime createdAt
  DateTime updatedAt
  Int reviewsRating
  String storeId FK
  Int price
  Int discountRate
  DateTime discountStartTime "nullable"
  DateTime discountEndTime "nullable"
  String categoryId FK
}
```

### `Product`

상품 모델입니다.

Properties as follows:

- `id`:
- `name`:
- `image`:
- `createdAt`:
- `updatedAt`:
- `reviewsRating`:
- `storeId`:
- `price`:
- `discountRate`:
- `discountStartTime`:
- `discountEndTime`:
- `categoryId`:

## Category

```mermaid
erDiagram
"Category" {
  String name
  String id PK
}
```

### `Category`

카테고리 모델입니다.

Properties as follows:

- `name`:
- `id`:

## Stock

```mermaid
erDiagram
"Stock" {
  String id PK
  String productId FK
  Int sizeId FK
  Int quantity
}
```

### `Stock`

재고 모델입니다.

Properties as follows:

- `id`:
- `productId`:
- `sizeId`:
- `quantity`:

## Size

```mermaid
erDiagram
"Size" {
  Json size
  String name UK
  Int id PK
}
```

### `Size`

사이즈 모델입니다.

Properties as follows:

- `size`: 다국어 지원을 위해 Json 을 사용합니다.
- `name`:
- `id`:

## Inquiry

```mermaid
erDiagram
"Inquiry" {
  String id PK
  String userId FK
  String productId FK
  String title
  String content
  AnswerStatus status
  Boolean isSecret
  DateTime createdAt
  DateTime updatedAt
}
```

### `Inquiry`

문의 모델입니다.

Properties as follows:

- `id`:
- `userId`:
- `productId`:
- `title`:
- `content`:
- `status`: 문의 처리 상태를 enum 으로 표시합니다.
- `isSecret`: 비밀글 설정을 할 수 있습니다.
- `createdAt`:
- `updatedAt`:

## Reply

```mermaid
erDiagram
"Reply" {
  String id PK
  String inquiryId FK,UK
  String userId FK "nullable"
  String content
  DateTime createdAt
  DateTime updatedAt
}
```

### `Reply`

답변 모델입니다.

Properties as follows:

- `id`:
- `inquiryId`:
- `userId`:
- `content`:
- `createdAt`:
- `updatedAt`:

## Review

```mermaid
erDiagram
"Review" {
  String id PK
  String userId FK
  String productId FK
  Int rating
  String content
  DateTime createdAt
  DateTime updatedAt
  String orderItemId FK,UK
}
```

### `Review`

리뷰 모델입니다.

Properties as follows:

- `id`:
- `userId`:
- `productId`:
- `rating`:
- `content`:
- `createdAt`:
- `updatedAt`:
- `orderItemId`:

## Cart

```mermaid
erDiagram
"Cart" {
  String id PK
  String buyerId FK,UK
  DateTime createdAt
  DateTime updatedAt
}
```

### `Cart`

장바구니 모델입니다.

Properties as follows:

- `id`:
- `buyerId`:
- `createdAt`:
- `updatedAt`:

## CartItem

```mermaid
erDiagram
"CartItem" {
  String id PK
  String cartId FK
  String productId FK
  Int sizeId FK
  Int quantity
  DateTime createdAt
  DateTime updatedAt
}
```

### `CartItem`

장바구니에 담긴 아이템 모델입니다.

Properties as follows:

- `id`:
- `cartId`:
- `productId`:
- `sizeId`:
- `quantity`:
- `createdAt`:
- `updatedAt`:

## Order

```mermaid
erDiagram
"Order" {
  String id PK
  String userId FK
  String name
  String phoneNumber
  String address
  Int subtotal
  Int totalQuantity
  Int usePoint
  DateTime createdAt
  DateTime updatedAt
}
```

### `Order`

주문 모델입니다.

Properties as follows:

- `id`:
- `userId`:
- `name`:
- `phoneNumber`:
- `address`:
- `subtotal`: 포인트를 제외한 상품 가격의 총합
- `totalQuantity`:
- `usePoint`:
- `createdAt`:
- `updatedAt`:

## OrderItem

```mermaid
erDiagram
"OrderItem" {
  String id PK
  Int price
  Int quantity
  String productId FK
  Int sizeId FK
  String orderId FK
  Boolean isReviewed
}
```

### `OrderItem`

주문한 아이템 모델입니다.

Properties as follows:

- `id`:
- `price`:
- `quantity`:
- `productId`:
- `sizeId`:
- `orderId`:
- `isReviewed`: 리뷰 썼는지 안썼는지 체크하는 boolean

## Payment

```mermaid
erDiagram
"Payment" {
  String id PK
  Int price
  PaymentStatus status
  DateTime createdAt
  DateTime updatedAt
  String orderId FK,UK
}
```

### `Payment`

결제 모델입니다.

Properties as follows:

- `id`:
- `price`:
- `status`: 결제 상태를 enum 으로 체크합니다.
- `createdAt`:
- `updatedAt`:
- `orderId`:

## Alarm

```mermaid
erDiagram
"Alarm" {
  String id PK
  String userId FK
  String content
  Boolean isChecked
  DateTime createdAt
  DateTime updatedAt
}
```

### `Alarm`

알림 모델입니다.

Properties as follows:

- `id`:
- `userId`:
- `content`:
- `isChecked`: 알림을 읽었는지 boolean 으로 체크합니다.
- `createdAt`:
- `updatedAt`:

## default

```mermaid
erDiagram
"DailyStoreSales" {
  String id PK
  String storeId FK
  DateTime date
  Int totalSales
  Int totalOrders
  DateTime createdAt
}
"WeeklyStoreSales" {
  String id PK
  String storeId FK
  Int week
  Int year
  Int totalSales
  Int totalOrders
  DateTime createdAt
}
"MonthlyStoreSales" {
  String id PK
  String storeId FK
  Int month
  Int year
  Int totalSales
  Int totalOrders
  DateTime createdAt
}
"yearlyStoreSales" {
  String id PK
  String storeId FK
  Int year
  Int totalSales
  Int totalOrders
  DateTime createdAt
}
```

### `DailyStoreSales`

Properties as follows:

- `id`:
- `storeId`:
- `date`:
- `totalSales`:
- `totalOrders`:
- `createdAt`:

### `WeeklyStoreSales`

Properties as follows:

- `id`:
- `storeId`:
- `week`:
- `year`:
- `totalSales`:
- `totalOrders`:
- `createdAt`:

### `MonthlyStoreSales`

Properties as follows:

- `id`:
- `storeId`:
- `month`:
- `year`:
- `totalSales`:
- `totalOrders`:
- `createdAt`:

### `yearlyStoreSales`

Properties as follows:

- `id`:
- `storeId`:
- `year`:
- `totalSales`:
- `totalOrders`:
- `createdAt`:
