# Refrigeration Cyber Response Elements

## One-sentence benefit
Helps CSIRTs and refrigeration operators coordinate exposed controllers, operational impact and accountable mitigations.

## Live demo
Run the Java service and Lit application locally to use the complete experience.

## Screenshots
![refrigeration cyber response workspace](docs/screenshot.png)

## Main features
Search refrigeration response cases, create a Belgian controller incident, advance mitigation and see live priorities through reusable components.

## Technology used
Lit, TypeScript, reactive controllers, web components, Vite, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm run dev`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
CSIRTs, food retailers, hospitals, cold-chain operators and equipment suppliers need a shared view of controller exposure and accountable controls.

## Key workflows
Users can filter response cases, create a validated controller incident, progress it and review current priorities.

## Lit and Web Components highlights
The interface uses standards-based custom elements, reactive properties, shadow DOM, a reactive controller and keyed rendering.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
The main custom element fetches API state, renders reusable status cards and replaces updated records after server writes.

## Accessibility and responsive behaviour
Labelled inputs, semantic headings, text status, visible focus, strong contrast and responsive grids support accessible use.

## Verification commands
Use `npm test`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the web components, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
The sample keeps data in memory; production use would add persistent evidence, identity controls, asset inventories and incident-management integrations.

## Roadmap
Add controller fingerprints, firmware advisories, site dependencies, coordinated disclosure and durable audit storage.
