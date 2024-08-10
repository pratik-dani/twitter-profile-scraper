#### Twitter Profile Scraper

Interested in scraping Twitter profiles? Get it here: [Twitter Profile Scraper](https://datamagnet.co). Extract detailed information from Twitter profiles and posts efficiently.

**Pricing**  
For better pricing, you can sign up here: [Datamagnet Pricing](https://datamagnet.co)

**Features**

- **Data Export and Integration:** Export the extracted data in JSON or CSV format. Customize the fields to integrate with other tools and platforms for in-depth analysis.
- **Automatic Retry and Error Handling:** The scraper includes built-in retry functionality to handle network issues or timeouts gracefully, ensuring uninterrupted data collection.
- **Ability to Resume Last Failed Runs:** Resume data collection from the last failed attempt with a simple click, allowing you to pick up where you left off.

**Integrations**

Use [Make](https://www.make.com/en/register) to integrate the Twitter Profile Scraper with other SaaS platforms, creating custom automation flows.

**Sample Output**

Here is a sample output of this scraper:

```json
{
  "biography": null,
  "birth_date": null,
  "category_name": null,
  "date_joined": "2009-06-02T20:12:29.000Z",
  "external_link": null,
  "followers": 193576643,
  "following": 690,
  "id": "elonmusk",
  "input": {
    "url": "https://x.com/elonmusk"
  },
  "is_business_account": false,
  "is_government_account": false,
  "is_verified": true,
  "location": null,
  "posts": [
    {
      "date_posted": "2022-04-28T00:56:58.000Z",
      "description": "Next I’m buying Coca-Cola to put the cocaine back in",
      "hashtags": [],
      "likes": 4457583,
      "photos": null,
      "post_id": "1519480761749016577",
      "post_url": "https://twitter.com/44196397/status/1519480761749016577",
      "replies": 182384,
      "reposts": 623761,
      "videos": null,
      "views": null
    }
  ],
  "posts_count": 49004,
  "profile_image_link": "https://pbs.twimg.com/profile_images/1815749056821346304/jS8I28PL_normal.jpg",
  "profile_name": "Elon Musk",
  "subscriptions": 158,
  "suggested_profiles": [
    {
      "profile_id": "50393960",
      "profile_image": "https://pbs.twimg.com/profile_images/1674815862879178752/nTGMV1Eo_normal.jpg",
      "profile_name": "Bill Gates",
      "profile_url": "https://x.com/BillGates"
    }
  ],
  "url": "https://x.com/elonmusk",
  "x_id": "44196397"
}
```

### Output Data Documentation

Here is the JSON fields documentation without including the sample values:

- **biography** (string): A short biography of the user.
- **birth_date** (string): The birth date of the user.
- **category_name** (string): The category or type of account.
- **date_joined** (string): The date when the user joined Twitter.
- **external_link** (string): Any external link associated with the user’s profile.
- **followers** (number): The number of followers the user has.
- **following** (number): The number of accounts the user is following.
- **id** (string): The user’s internal Twitter ID.
- **input** (object): Contains the URL of the user’s Twitter profile.
- **is_business_account** (boolean): Indicates if the account is a business account.
- **is_government_account** (boolean): Indicates if the account is a government account.
- **is_verified** (boolean): Indicates if the account is verified.
- **location** (string): The location of the user.
- **posts** (array): An array of posts by the user.
- **posts_count** (number): The total number of posts made by the user.
- **profile_image_link** (string): The URL of the user’s profile image.
- **profile_name** (string): The name of the user.
- **subscriptions** (number): The number of subscriptions the user has.
- **suggested_profiles** (array): A list of suggested profiles related to the user.
- **url** (string): The URL of the user’s Twitter profile.
- **x_id** (string): The user’s unique ID on Twitter.
