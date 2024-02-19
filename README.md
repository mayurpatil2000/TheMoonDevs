# BurnPage Refactoring

This project demonstrates the refactoring of a BurnPage component into modular and reusable components.

## Project Structure

- `BurnPage`: Main component that holds the state and structure of the Burn page.
- `BurnButtonBar`: Component responsible for rendering the burn button and related functionality.
- `BurnStatsContainer`: Component displaying App supply statistics and related information.
- `TransactionTableStyled`: Component for styling the transaction table.
- `ChainSelector`: Component for selecting the token chain.
- `AppToast`: Component for displaying toast messages.
- `DashboardLayoutStyled`: Component for the main dashboard layout.

## Before and After

- The `before` folder contains the original code.
- The `after` folder contains the refactored code with components separated.

## How to Use

1. Clone the repository.
2. Navigate to the `after` folder.
3. Install dependencies with `npm install` or `yarn install`.
4. Start the application with `npm start` or `yarn start`.

## Justification

- **Readability:** Breaking down the BurnPage into smaller components improves code readability.
- **Maintainability:** Each component has a single responsibility, making it easier to maintain and update.
- **Reusability:** Components can be reused in other parts of the application.

## Contributions

Feel free to contribute by opening issues or pull requests. Suggestions and improvements are always welcome!
