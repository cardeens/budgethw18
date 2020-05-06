# budgethw18

## Description

We created a money tracker that can quickly and easily allow someone to track their expenses throughout their days. This application also has the ability to work while the use is offline, and can automatically stay up-to-date with the transactions and amounts as the user switches between online/offline scenarios. This is important for business travelers because they constantly travel on planes, cars, etc. and rack up work expenses on the way. This allows them to easily track their expenses even if they are in a position where they are offline, like in an airplane.

It's important to note that serviceworker.js file is a JS file that helps handle the offline functionality, and the manifest.js file helps handle how the app will look as a native app. 

## Usage

The end user can add an expense name and amount to remove the money from their total, and also add deposits as needed for things like payday that will increase their total amount. The user can then see their past transactions and amounts to keep track of their budget.

## Testing

The user should be able to go into Offline mode by going to Network > Offline in their console and enter withdrawals/deposits just as they would in online mode. Once they go back into Online mode, they should see all the same transaction amounts and their total should NOT reset to what it was before going into offline mode.