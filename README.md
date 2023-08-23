# thelook_ecommerce_purchase_behaviour
Purchase Behaviour Data Model in BigQuery SQL.

DATA MODEL EXPLANATION

user_id: This is a unique identifier assigned to each user in your database. It's the primary key that can be used to identify a user in the users table.

email: This is the email address associated with the user. It is a critical piece of contact information.

age: This represents the age of the user.

gender: This indicates the gender of the user.

country: This is the country where the user resides.

traffic_source: This indicates the source from where the user was directed to the ecommerce platform. It could be from search engines, social media, email marketing, etc.

cohort_date: This is the date of the user's first order. This field is useful to define cohorts for further analysis.

latest_shopping_date: This is the date of the user's most recent order. It can be used to evaluate recent activity or inactivity of users.

lifespan_months: This is the number of months between the user's first and most recent order. This can be used to understand user retention and lifecycle.

ltv: This stands for "Lifetime Value". It's the total sales value associated with a specific customer, calculated by summing up the sale price of all orders placed by the user.

purchase_frequency: This indicates the total number of distinct orders the user has made. It's useful for understanding how often a user engages in purchasing.

average_order_value: This represents the average monetary value of each order the user has placed, calculated by dividing the total sales value (ltv) by the total number of distinct orders the user has made. This provides an indication of how much a user typically spends on each order.
