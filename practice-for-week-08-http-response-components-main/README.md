# Exercise: HTTP Response Components

Clone the exercise from the [starter].

Based on the following scenarios discuss and determine what the HTTP response
components should be in each scenario.

For example, the response components for viewing the home page of Google could
include:

- status code: 200
- headers:
  - Content-Type: text/html
- body: home page

The body doesn't have to be exact. Instead, describe what the contents of the
body might include for the scenario.

## Scenarios

1. Click a link to an Instagram post that your friend thought was funny.
   - status code: 200
   - headers:
      - Content-Type: text/html
      - body: the post
2. Edit a Facebook comment that isn't your own
   - status code: 401 unauthorized
   - headers:
      - Content-Type: ?
      - body: ?
3. Upload your sick mixtape to SoundCloud successfully
   - status code: 201 or 302 if redirect to profile?
   - headers:
      - Content-Type: ?
      - body: the song or your profile?
4. Attempt to submit an Amazon review for a product through an HTML form, but
   you aren't logged in yet
   - status code: 401 unauthorized
   - headers:
      - Content-Type: html
      - body: login page
5. Sell one of your stocks on Robinhood, but Robinhood is having issues with
   their server because so many people are trying to sell that stock. The
   browser is displaying what seems like an infinite loading screen.
   - status code: 503
   - headers:
      - Content-Type: ?
      - body: ?
6. Browse GIPHY for a cute puppy gif but there are no cute puppy gifs!
   - status code: 404
   - headers:
      - Content-Type: ?
      - body: ?
7. Send a picture to a friend on Snapchat
   - status code: 201
   - headers:
      - Content-Type: ?
      - body: ?

[starter]: https://github.com/appacademy/practice-for-week-08-http-response-components
