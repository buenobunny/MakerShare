# CalHacks2020

## Inspiration

Our team has family members and friends who are working as essential workers. Many of them do not have proper safety equipment like masks and cleaning supplies. As many community members are making their own DIY masks and have surplus cleaning/medical supplies, we wanted to create a way where we can connect essential workers lacking medical supplies to generous community members who can make or already have these supplies.

## How it works

A user can log in as either an essential worker or a community member. After logging in, they can access an integrated Google Map, where they view nearby listings. An essential worker will have the option to request supplies as a listing or accept available listings from a community member. A community member will have the option to accept an essential worker's request listing or create their own listing. Each listing will include a title, an optional image (required when a community member makes their own listing), description, and contact information. After a listing is accepted, each party is informed and pick up details are left to both parties to decide. It is up to the community member and essential worker to decide who wants to pick up or drop off the supplies. 

## How we built it

We used Google's Firebase and Maps APIs for the backend construction. Namely, we used Firebase's hosting, authentication and database services. With the services we are able to put out the website, sign in users and create listings for the community to interact with, respectively. We used the database's unique JSON formatting with Javascript to allow population of a listings page and creation of new listings.

## Challenges

Some challenges were incorporating the functionality of the Google Maps API effectively and in conjunction with the listings. Currently, it does not display the addresses of the listings because we did not have the resources or time to implement. Additionally, we were not able to fully incorporate a framework for accepting listings as of yet.

## Accomplishments that we are proud of

## What's next for MakerShare
