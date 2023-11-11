# first-project
# TADA App Test Plan #
라이트 헤일링 앱에서의 핵심 기능은 고객이 빠르고 쉽게 차량을 부를 수 있는 기능 이다. 
이를 위해 고객의 위치정보를 정확히 파악 해야 하고 운전자와 고객간의 call이 원활해야 한다 
해당기능이 정상동작 하는지 확인하기 위해 테스트를 진행한다. 

## 테스트 대상 ##
TADA test App (IOS)

## 테스트 목적 ##
필수 기능의 정상 동작 여부를 검증한다.
예상치 못한 오류나 버그를 발견한다.

## 테스트 범위 ##
상품 검색 후 call 넣는 기능에 대한 필수 시나리오  
SG - Book CAR/TAX
VN - ANY TADA, ECONOMY LARGE, BIKE
KH - TukTuk, Car, SUV

## TEST CASE ##
### Test data ###
**테스트 계정**
- +6531110021 

**OTP Code** 
- 000000 

**test location address**

- SG: Ubi road 1 ( lat: 1.332416, lng: 103.8903482 )
- VN: HCM, Cho Tan Binh ( lat: 10.785953, lng: 106.6525095 )
- KH: Royal Palace, Cambodia ( lat: 11.5639796, lng: 104.9304278 )

### 1. Singapore test ###

**Precondition**
1. iOS mobile device with TADA app installed
2. Log in 
3. Set the location to Singapore.

**Test Case 1-1**
**test step**
1. Click "Book CAR/TAXI"
2. After confirming the departure location, click "Set pickup location".
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".
6. Select "General call" and click "Request".

**test result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

**Test Case 1-2**
**test step**
1. Click "Book CAR/TAXI"
2. After confirming the departure location, click "Set pickup location".
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".
6. Select "Smart call" and click "Request".

**test result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

### 2. Vietnam test ###

**Precondition**
1. iOS mobile device with TADA app installed
2. Log in 
3. Set the location to vietnam

**Test Case 2-1**
**step** 
1. Click "ANY TADA".
2. After confirming the departure location, click "Set pickup location".
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".

**result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

**Test Case 2-2**
**step** 
1. Click "ECONOMY LARGE".
2. After confirming the departure location, click "Set pickup location".
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".

**result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

**Test Case 2-3**
**step** 
1. Click "BIKE".
2. After confirming the departure location, click "Set pickup location".
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".

**result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

### 3. Cambodia test ###

**Precondition**
1. iOS mobile device with TADA app installed
2. Log in 
3. Set the location to Cambodia 

**Test Case 3-1**
**test step**
1. Click the "Tuk Tuk"
2. After confirming the departure location and payment method, click "Book"

**test result**
1. The location settings map screen is displayed.
2. The fare and payment method for the selected transportation method are displayed.
3. The call is executed.

**Test Case 3-2**
**test step**
1. Click "Tuk Tuk"
2. Click "+ Where to "
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".

**test result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

**Test Case 3-3**
**test step**
1. Click "Car"
2. After confirming the departure location and payment method, click "Book"

**test result**
1. The location settings map screen is displayed.
2. The fare and payment method for the selected transportation method are displayed.
3. The call is executed.

**Test Case 3-4**
**test step**
1. Click "Car"
2. Click "+ Where to "
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".

**test result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

**Test Case 3-5*
**test step**
1. Click "SUV"
2. After confirming the departure location and payment method, click "Book"

**test result**
1. The location settings map screen is displayed.
2. The fare and payment method for the selected transportation method are displayed.
3. The call is executed.

**Test Case 3-6**
**test step**
1. Click "SUV"
2. Click "+ Where to "
3. Click “Map” in the top right.
4. Move the pin location on the map to set the destination and Click "Set destination location".
5. After checking the rate and payment method, click "Book".

**test result**
1. The location settings map screen is displayed.
2. You can move the pin to the desired point on the map.
3. The route to the selected destination, fare, and payment method are displayed.
4. The call is executed.

## 작성자 및 작성일 ##
- 작성자 : 옥다윤
- 작성일 : 23/11/11
