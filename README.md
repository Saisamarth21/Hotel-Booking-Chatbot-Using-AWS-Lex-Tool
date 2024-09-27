# Hotel-Booking-Chatbot-Using-AWS-Lex-Tool
This project involves the creation of a chatbot using Amazon Lex. The chatbot facilitates users in selecting room types, providing Name, Phone Number, checkin and check-out dates, and confirming their reservations, while also delivering pricing information.

# Steps used to Create the Chatbot

## Step 1: Set Up Your AWS Account
* Log into the AWS Management Console.
* Navigate to Amazon Lex.

## Step 2: Create a New Bot
1. Click on "Create Bot."
2. Provide a name
3. Choose a language
4. Set the voice (optional) and enable text or voice responses.
5. Select or create an IAM role for the bot.
<img width="1041" alt="Screenshot 2024-09-27 at 7 38 06 PM" src="https://github.com/user-attachments/assets/10fc229f-b228-4243-8e32-334ac7f0c9b9">

## Step 3: Define the Intent
1. Click on "Intents" in the sidebar.
2. Click on "Create Intent."
3. Name the intent
<img width="1041" alt="Screenshot 2024-09-27 at 7 39 10 PM" src="https://github.com/user-attachments/assets/128ad3cd-5e33-4a29-b68d-bb430ba593ed">


## Step 4: Define Slots
Create the following slots to collect necessary booking information:
1. Name: Type `AMAZON.FirstName` .
2. Phone Number: Type `AMAZON.NUMBER` .
3. CheckInDate: Type `AMAZON.DATE` .
4. CheckOutDate: Type `AMAZON.DATE` .
5. NumberOfGuests: Type `AMAZON.NUMBER` .
6. RoomType: Custom Slot Type with values such as Standard , Deluxe , and Suite.
<img width="800" alt="Screenshot 2024-09-27 at 7 40 38 PM" src="https://github.com/user-attachments/assets/809fa4eb-8950-4753-9a92-8909a6b2c8a2">

## Step 5: Configure Slot Types
Ensure the `RoomType` slot is set up with the defined values.
<img width="612" alt="Screenshot 2024-09-27 at 7 41 50 PM" src="https://github.com/user-attachments/assets/06791bb9-04b8-4241-8f1e-2d93a1d5d023">

## Step 6: Add Sample Utterances
Add sample utterances for the intent, such as:
* "Hi"
* "Hello"
* "hi"
<img width="805" alt="Screenshot 2024-09-27 at 7 42 55 PM" src="https://github.com/user-attachments/assets/66791bda-74cd-4def-b27d-67fadad7ce22">

## Step 7: Test the Bot
Test the bot in the Amazon Lex console to ensure it captures slot values and
provides appropriate responses.

<img width="348" alt="Screenshot 2024-09-27 at 7 45 00 PM" src="https://github.com/user-attachments/assets/afa01da7-cb0e-4d5c-93ee-a12f65916144"><img width="348" alt="Screenshot 2024-09-27 at 7 44 43 PM" src="https://github.com/user-attachments/assets/f5439eea-d8fd-43d4-935f-6b47e99719c8">

