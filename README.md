# NLP-model-for-an-e-commerce-website
implementing an NLP model for an e-commerce website that can understand and appropriately respond to customer requests in text format.

ou are tasked with implementing an NLP model for an e-commerce website that can understand and appropriately respond to customer requests in text format. The system is limited to two services: Listing, and Check Wallet Balance.

The system should be able to recognize and extract relevant information from user queries, such as category, brand, size, and price range. It should also be able to handle variations in phrasing and grammar, such as "Which items do you have?", "What do you sell?", or "Can you show me your inventory?" - all of which should call the inventory listing services to obtain a list of available items.

In addition, the system must be able to understand requests that include specific details, such as "I want to buy a Gucci cloth with size XL," which contains two important tokens (Brand and Cloth Size). So this will call the listing service with brand and cloth size parameters so as to query for only matched entities

Similarly,
"my account balance"
"How much do i have left"
"my wallet status"

All should be calling the wallet service

