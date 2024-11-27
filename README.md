# Common-Statistical-Test---case_study_1

# AZ Tunes Case Study

## Problem Statement

### Business Context

AZ Tunes is a music streaming company that analyzes customer data to improve recommendations, playlists, and rollout special offers. Their persistent efforts to uncover and act upon evolving customer expectations have resulted in higher customer engagement time and subscriptions to their paid service.

### Objective

The **Marketing team** at AZ Tunes is planning to roll out special offers through a new campaign. As a data scientist, your objective is to help the team design the campaign by providing data-driven insights on the following:

1. According to a study, the average weekly app engagement time of users in leading music services is around 6 hours. Can we claim that the app engagement time of AZ Tunes is better than this market standard?
2. The team wants to allocate their budget to the age group that has the highest chance of subscribing as part of their campaign.

You need to perform statistical analysis on a sample of customer data and provide evidence-based conclusions to help the marketing campaign succeed.

## Data Dictionary

You are provided with a random sample of 1000 users, including the following attributes:

- **user_id**: Unique ID of the user
- **age_group**: Age group the user belongs to
  - Under 18
  - 18-34
  - Over 35
- **subscription_status**: Whether the user is a subscribed user or a non-subscribed user
- **engagement_time**: Weekly average of app engagement time (in hours) of the user

## Solution Approach

To solve the problem, we need to answer two questions:

1. Is the average app engagement time of AZ Tunes significantly greater than the market average of 6 hours?
2. Is the difference in proportions of subscribers and non-subscribers in the age groups (Under 18, 18-34, and Over 35) significantly different to conclude that a particular group is most likely to subscribe?
