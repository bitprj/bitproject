# Engineering

{% api-method method="get" host="https://darlene-backend.herokuapp.com/" path="activities/{{activity\_id}}" %}
{% api-method-summary %}
FetchActivity
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get free cakes.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="actvitiy\_id" type="integer" required=true %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="jwt\_token" type="string" required=true %}
A JWT token to keep track of the user's information. 
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Activity found
{% endapi-method-response-example-description %}

```
{
    "id": 86,
    "name": "Time and Space Complexity",
    "description": "Learn about the different rates at which algorithm's memory usage and runtime increase",
    "summary": "Algorithms require an input to run. As the input grows, learn about what happens to the memory usage and space usage. Learn about how to describe this rate.",
    "is_project": false,
    "image": "https://projectbit.s3-us-west-1.amazonaws.com/Github/activities/Time.jpg",
    "cards": [
        {
            "id": 303
        },
        {
            "id": 302
        },
        {
            "id": 301
        },
        {
            "id": 300
        },
        {
            "id": 299
        },
        {
            "id": 298
        },
        {
            "id": 297
        },
        {
            "id": 296
        }
    ],
    "prerequisite_activities": []
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Activity does not exist.
{% endapi-method-response-example-description %}

```
{
    "message": "Activity does not exist"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://darlene-backend.herokuapp.com/" path="cards/{{card\_id}}" %}
{% api-method-summary %}
FetchCard
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="card\_id" type="integer" required=true %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Card found
{% endapi-method-response-example-description %}

    {
        "id": 325,
        "activity_id": 90,
        "content": "Now we have our array of stored unicode for graphic, `grid`.\n(32 for space, 9608 for wall and 9618 for exit- refer to \"Load File as Map\")\nwe can now print out our maze!\n\nWrite a `printGrid(grid)` function that takes in `grid` and print them out accordingly.\n",
        "gems": 100,
        "name": "Print Grid",
        "concepts": [],
        "hints": [
            {
                "id": 428,
                "hints": [
                    {
                        "id": 429,
                        "hints": []
                    }
                ]
            }
        ],
        "checkpoint": {
            "id": 77
        }
    }
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Card does not exist
{% endapi-method-response-example-description %}

```
{
    "message": "Card does not exist"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

