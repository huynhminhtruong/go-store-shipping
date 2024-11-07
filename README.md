# go-store-shipping

# Business Logic

### 1. List of orders

- Get list of orders from go-store-order service
  
### 2. Make a shipping request

- Create shipping after order was created from go-store-order service
- Implement gRPC service to create shipping

### 3. Update a shipping request

- Shipping should be cancel if the order has been cancel
- Implement gRPC service to handle this job

### 4. Get an shipping by id

- Implement gRPC service to get a shipping
- Gen grpc-gateway code for HTTP GET request

### 5. Get list of shipping

- Implement gPRC service to get list of shipping
  - Admin role: get all
  - Customer role: get shipping which related current user only
- Gen grpc-gateway code for HTTP GET request

### 6. Filter shipping by [id | status | location]

- Implement gRPC service to search or filter orders
- Gen grpc-gateway code for HTTP GET request
