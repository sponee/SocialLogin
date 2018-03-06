# TODO

1. Create a concept of identities.
   * Users should to be able to login with multiple providers, not just one.
   * Create an Identity class that holds provider information. An Identity should belong to a User.
   * https://github.com/omniauth/omniauth/wiki/Managing-Multiple-Providers
2. Create a table for the User model.
   * Give some thought to this before you do it. You don't want to have a bunch of migrations moving data from one table to another.
3. Allow login with Facebook.
4. Allow login with Gmail, Google +, Google. 
   * At the end of the day people should be able to use a 
   * Not sure how they're different exactly, but they are - https://github.com/omniauth/omniauth/wiki/List-of-Strategies
