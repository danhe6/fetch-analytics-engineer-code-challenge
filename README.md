# Guidance
## Structured Relational Data Model Overview
![ER Diagram](er_diagram.png)

## Table Information Overview

### receipt

**receipt_id**: **primary key**, unique id for this receipt   
**user_id**: **foreign key** from user table, unique id for user  
**bonus_reason_id**: **foreign key** from bonus_reason table, unique id for bonus points earned reason  
**receipt_status_id**: **foreign key** from receipt_status table, unique id for rewards receipt status  
**create_date**: the date that the event was created    
**scanned_date**: date that the user scanned their receipt  
**finished_date**: date that the receipt finished processing 
**modify_date**: the date the event was modified  
**points_awarded_date**: the date we awarded points for the transaction 
**purchase_date**: the date of the purchase 
**bonus_points_earned**: the number of bonus points earned for the receipt  
**points_earned**: the number of points earned for the receipt  
**purchase_item_count**: count of number of items on the receipt 
**total_spent**: the total amount on the receipt  

### Brand

**brand_id**:
**barcode**:
**cpg**:
**name**:
**top_brand**:
**brand_code**:
**category_id**:

### User
