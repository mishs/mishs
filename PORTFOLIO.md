# Selected Engineering Work

Nine public projects by Misheck Siwela, grouped to make the implementation easy to explore.

[Back to profile](https://github.com/mishs)

## Where to start

- **Frontend architecture and interaction:** Management Dashboard, GitHub Commits Explorer.
- **Data visualisation:** Europe Data Visualisation.
- **TypeScript modelling and tests:** Martian Robots.
- **Business interfaces:** Client Subscription Tracker, PC Games Catalogue.
- **Forms and user journeys:** Card Form Interface, Delivery Pickup Selector, Bar Tab Orders.

## Project guide

### 1. Management Dashboard

React and TypeScript task board with drag-and-drop ordering, Redux Toolkit, mocked API workflows, and Storybook components.

**Focus:** Complex UI state and component development.

- [Repository and setup](https://github.com/mishs/management-dashboard)
- [Implementation entry point](https://github.com/mishs/management-dashboard/blob/main/frontend/src/storybookComponents/Dashboard/Dashboard.tsx)
- [Task helper tests](https://github.com/mishs/management-dashboard/blob/main/frontend/src/utils/taskHelpers.test.ts)

### 2. Europe Data Visualisation

Angular and D3 circle-packing visualisation with population/land-area switching and country detail selection.

**Focus:** Interactive data visualisation.

- [Repository and setup](https://github.com/mishs/europe-circle-packing)
- [Implementation entry point](https://github.com/mishs/europe-circle-packing/blob/development/src/app/features/circle-packing/circle-packing.component.ts)
- [Data loading](https://github.com/mishs/europe-circle-packing/blob/development/src/app/utils/data-loader.ts)

### 3. Martian Robots

TypeScript command-line simulation with domain models, command handling, input validation, and simulation tests.

**Focus:** Domain modelling and automated tests.

- [Repository and setup](https://github.com/mishs/martlan-robots)
- [Implementation entry point](https://github.com/mishs/martlan-robots/blob/main/src/simulator/RobotSimulator.ts)
- [Simulation tests](https://github.com/mishs/martlan-robots/blob/main/tests/RobotSimulator.test.ts)

### 4. GitHub Commits Explorer

React assessment project for browsing repository commits, with shared state managed through Context and a reducer.

**Focus:** Repository exploration and shared UI state.

- [Repository and setup](https://github.com/mishs/react-gitcommits-explorer)
- [Implementation entry point](https://github.com/mishs/react-gitcommits-explorer/blob/main/src/context/CommitsContext.js)
- [Commits interface](https://github.com/mishs/react-gitcommits-explorer/blob/main/src/Commits/Commits.js)

### 5. Client Subscription Tracker

React interface for exploring device, licence, and subscription information with search, filters, and local mock data.

**Focus:** Business interfaces and filtering.

- [Repository and setup](https://github.com/mishs/client-subscriptions-tracking)
- [Implementation entry point](https://github.com/mishs/client-subscriptions-tracking/blob/main/src/Context/DevicesContext.js)
- [Table interface](https://github.com/mishs/client-subscriptions-tracking/blob/main/src/components/Layout/MainTable.jsx)

### 6. PC Games Catalogue

React catalogue for exploring game deals and detail views, with API-backed data and search controls.

**Focus:** API-backed catalogue and detail views.

- [Repository and setup](https://github.com/mishs/react-online-catalogue-web-system)
- [Implementation entry point](https://github.com/mishs/react-online-catalogue-web-system/blob/main/src/context/DealsState.js)
- [Deal detail view](https://github.com/mishs/react-online-catalogue-web-system/blob/main/src/pages/DealDetail/DealDetail.jsx)

### 7. Card Form Interface

React and TypeScript form project with card-entry, edit flows, validation logic, and a visual card preview.

**Focus:** Forms and interaction design.

- [Repository and setup](https://github.com/mishs/credit-card-validation)
- [Implementation entry point](https://github.com/mishs/credit-card-validation/blob/main/src/components/CardForm/index.tsx)
- [Edit flow](https://github.com/mishs/credit-card-validation/blob/main/src/CardManager/EditCard/EditCard.tsx)

### 8. Delivery Pickup Selector

React assessment interface for exploring pickup locations, expanding address details, and selecting a location.

**Focus:** Selection workflows and detail presentation.

- [Repository and setup](https://github.com/mishs/delivery-pickup)
- [Implementation entry point](https://github.com/mishs/delivery-pickup/blob/main/src/components/PickupCard/PickupCard.jsx)
- [Selection detail page](https://github.com/mishs/delivery-pickup/blob/main/src/pages/pickup-detail/user-detail.jsx)

### 9. Bar Tab Orders

React assessment project with price-list and order views, shared order state, and browser-local persistence.

**Focus:** Order flows and local persistence.

- [Repository and setup](https://github.com/mishs/bartab-frontend-react)
- [Implementation entry point](https://github.com/mishs/bartab-frontend-react/blob/main/src/App.js)

## Reading the evidence

The links point to source files and test files, where present. Test-file links show the available test implementation; they do not assert a current passing build or coverage percentage.

These repositories include demos and assessments with different scopes. The dashboard uses a mocked API, the subscription tracker uses local mock data, and the card form is an interface example rather than a payment-processing service.

[Return to profile](https://github.com/mishs)
