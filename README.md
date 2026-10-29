# Smart India Hackathon Workshop
# Date:29.10.2026
## Reference Number:26013026
## Name:S.FAYAS GANI

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Background:
Indian farmers often sell produce through a long chain of agents, commission agents, wholesalers, and retailers. Each layer adds its own margin, so farmers receive only a small share of the final price while consumers pay far more than the farm-gate rate.
Key Problems:
Farmers earn 25-40% of the consumer price on many perishables, and often less
Small farmers and FPOs have no direct access to consumers or bulk buyers
Price information is opaque, so farmers can't negotiate
Poor logistics and cold-chain gaps cause 20-30% post-harvest losses on fruits and vegetables
Supply and demand are mismatched, causing gluts, price crashes, and shortages
Delayed payments force distress sales
Who Is Affected:
Small and marginal farmers and FPOs: low income and high risk
Consumers: high prices and inconsistent quality
Bulk buyers (retailers, restaurants, processors): unreliable supply
Government: food price inflation and wastage
Expected Solution:
A digital marketplace that:
Connects farmers and FPOs directly with consumers and bulk buyers
Provides logistics support (pickup, pooled transport, cold chain)
Uses AI for demand forecasting and route optimization
Expected Benefits:
Better prices for farmers
Lower prices for consumers
Reduced supply chain inefficiencies and food wastage

## Proposed Solution
Idea: "FarmDirect," a digital marketplace where farmers and FPOs list produce and sell directly to consumers and bulk buyers (retailers, restaurants, hostels, processors).
How it addresses the problem:
Removes middlemen, so farmers get a higher share of the price and consumers pay less
Built-in logistics: pickup, pooled transport, and cold-chain partners
AI demand forecasting tells farmers what to grow and sell, and when
AI route optimization cuts delivery cost and delay
Innovation:
Pooled-order logistics, where small farmers share a vehicle
Transparent price breakdown (farmer share vs. transport vs. platform fee)
Voice and regional-language support
Forward bulk contracts with advance demand visibility

## Technical Approach
Technologies:
Frontend: Flutter (mobile), React (web)
Backend: Python (FastAPI) or Node.js, PostgreSQL
AI/ML: Prophet/LSTM/XGBoost for demand forecasting; OR-Tools or a genetic algorithm for route optimization
Maps: Google Maps/OpenStreetMap APIs
Payments: UPI/Razorpay escrow
Language: Bhashini APIs
Data: Agmarknet, eNAM, IMD
Methodology:
Onboard farmers/FPOs with produce listings and quality grading
Buyers browse, order, and pay through escrow
The forecasting engine predicts demand by area and crop
The route engine groups orders and assigns vehicles
Delivery tracking, then payment release to the farmer
Ratings and feedback loop
Flow: Farmer lists produce → buyer orders → AI matches and pools orders → route optimized → pickup and delivery → payment settled.

## Feasibility and Viability
Feasibility: Public price data, UPI, and mapping APIs exist, and the ML methods are proven. Start with a pilot in one district.
Challenges and mitigations:
Farmer trust and digital literacy → FPO-led onboarding, voice UI
Quality inconsistency → grading standards, photo verification, ratings
Perishability → cold-chain partners, short delivery radius
Logistics cost at low volume → pooled orders, local hubs
Payment disputes → escrow with release on delivery
Viability: Revenue from a small commission (2-5%), logistics margin, and bulk-buyer subscriptions.
## Impact and Benefits
Social: Empowers small farmers and FPOs and gives consumers fresher produce.
Economic: Higher farmer income, lower consumer prices, and less supply chain inefficiency.
Environmental: Less food wastage, fewer empty-return trips, and lower emissions.
## Research and References
Agmarknet: agmarknet.gov.in
eNAM: enam.gov.in
Open Government Data: data.gov.in
Bhashini: bhashini.gov.in
Add 2-3 Google Scholar papers on agri supply chain disintermediation and vehicle routing.
