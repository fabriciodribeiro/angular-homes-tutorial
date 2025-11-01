# angular-homes-tutorial

Minimal demo app exploring Angular 20 standalone components and router usage.

## What this project contains

- A small homes listing demo implemented with standalone components and DI.
- Key components and services:
  - [`App`](src/app/app.ts) — root component and layout.
  - [`Home`](src/app/home/home.ts) — list/filter view.
  - [`Details`](src/app/details/details.ts) — details view for a listing.
  - [`HousingService`](src/app/housing.ts) — in-memory housing data.
  - [`HousingLocation`](src/app/housing-location/housing-location.ts) — listing card component.
  - [`HousingLocationInfo`](src/app/housinglocation.ts) — data shape for listings.
  - Routes are defined in [`src/app/routes.ts`](/src/app/routes.ts).

## Quick start

Prerequisites: Node.js + npm.

Install dependencies and run locally:

```sh
npm install
npm run start


## Quick start - Container

Prerequisites: Docker desktop

Install dependencies and run locally:

```sh
docker build -t image_name .
docker run --rm -d --name container_name -p 4200:4200 -d image_name
