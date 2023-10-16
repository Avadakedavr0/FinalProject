# FinalProject
Final Project .NET fullstack bootcamp

Project description:
Amazon affiliate website with the top selling tech gadgets/must haves.

Phase 1
Get acces to the Product Avertising API.
Register domain.
Top items will be fetched from the PA-API (Amazon Product Advertising API)
That data will be stored in our database (Azure or domain db) and we will use an api in every microservice to:
Product Search API -> for checking database for existing results.
Product Detail API -> gives detailed information for a specific product.
User Activity Logging API -> logging user actions for analytics/google analytics input.
Library for shared utilities,models,..
Blazor will be used as frontend.

Phase 2
Adding user authentication
Adding review section to every item.
Add affiliate Amazon prime "30days free" page/affiliate link.
Deploy backend to cloud provider.

Phase 3
Making the affiliate links universal to automatically switch between different countries.
