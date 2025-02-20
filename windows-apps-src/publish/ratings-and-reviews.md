---
description: Prompt users for ratings and reviews, and analyze reviews provided by users
title: Ratings and reviews in the Microsoft Store
ms.date: 04/13/2022
ms.topic: article
ms.author: hickeys
author: hickeys
keywords: windows 10, uwp, rating, rate, review, star, stars, rated, analyze
ms.localizationpriority: medium
---

# Ratings and reviews in the Microsoft Store

Users can rate and review any products they’ve purchased or rented in the Microsoft Store. This helps others decide what products they should get next. Reviews also help developers get feedback to improve their apps. Ratings and reviews impact a product’s discoverability, which can boost downloads in Microsoft Store.

## Ratings

Users can rate an app, game, movie or TV show on a scale of one to five stars. The rating score is calculated based on a product’s recent ratings to give users insight to the current product experience.

The count of ratings includes most recent ratings submitted for the app, which are used to calculate the app's rating score. It’s visible on the product page and in search results.

The count of ratings and rating score are specific to a user’s country and type of device.

## Reviews

Reviews are a great way for users to share their experience with a product. Reviews are visible to everyone on the product page along with user’s name. If a review is edited, the latest review will be shown on the product page.

## Asking users for ratings and reviews

Apps can prompt users to give their ratings and reviews. It’s important to choose the right time to ask users for their feedback, such as when they’ve finished a task or have regular engagement with an app. Repeated requests for ratings can cause users to leave negative reviews.  

The [RequestRateAndReviewAppAsync](../monetize/request-ratings-and-reviews.md#show-a-rating-and-review-dialog-in-your-app) API can be used to solicit ratings and reviews from users without leaving your app. If you want to open the rating and review page for your app in the Microsoft Store, use the [LaunchUriAsync](../monetize/request-ratings-and-reviews.md#launch-the-rating-and-review-page-for-your-app-in-the-store) method.

## Analyzing ratings and reviews

Analyze ratings and reviews with the [Reviews](reviews-report.md) report in Partner Center. This helps developers monitor the performance of their app over time. For more details, developers can also analyze ratings and reviews by country, app package, device type, OS, and more.

## Reporting concerns

If review has spam, advertising, profanity, or offensive content, find the review on the product page and report it.
