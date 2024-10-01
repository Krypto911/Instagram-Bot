Instagram bot. It works without instagram api, need only login and password. Write on python.

After Instagram close api (new review process), there were some problem, to make auto - like, comment and follow.

If your app can't pass new review process, this is solution!

This InstaBot work by https://www.instagram.com and need only your login and password.
Usage


bot = InstaBot('login', 'password',
               like_per_day=1000,
               more_than_likes=10,
               tag_list = ['cat', 'car', 'dog'],
               max_like_for_one_tag=5,
               log_mod = 0)
               like_per_day=1000
