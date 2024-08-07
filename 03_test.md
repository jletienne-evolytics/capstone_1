
# First Test

Let's put the test file to use.
Let's look at what the developers at sleeper have in store for us.

They surely must have a website that properly documents their API
https://docs.sleeper.com/

Oh cool nice, maybe there's some league we can look at?
https://docs.sleeper.com/#get-a-specific-league


Look at that. We can pass a parameter ```<league_id>``` into the url to get the league info.

Let's see what's up, modify that .py file to what comes back. You remember the requests module from training so this is all review.


Let's import **requests** and run it.

![](screenshots/Capstone%204b.png)

Beautiful it failed. No module named requests. I got you

```
pip install requests
```

Nice it runs this time

![](screenshots/Capstone%205.png)


I'm getting this weird message ssl error something. Idk what this does but it fixed it right up
```
pip install urllib3==1.26.6
```


# Keep going

Let's keep working on this test.py file

How's this one look?

![](screenshots/Capstone%206.png)

At the top notice we're importing *yaml* now, since we created `config.yaml` in the previous lesson. So might get an error that yaml can't be found

Apologies, for glossing over this stuff right now. What's r? what's r.text? what's safe_load()

Great questions my friend. (Feel free to google if anything is too fast, reminder always reach out and ask questions if needed)

I may have skipped about JSON objects in the teaching. It's okay!
For our purposes it's almosst the same as a dictionary, you can read more about it here
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON


Just breathe and take it step by step. Here's an explanation of what's going on.

![](screenshots/Capstone%207.png)

Very important notice at the bottom, it says 200! 200 means valid! We're returning a dictionary!


Congrats you passed your first test! Believe in yourself


# What if you failed

If you failed, it's okay stay patient.

If you failed, you don't get 200, there's no data being returned in the terminal. Just reach out for help. You're almost there

[serious] It's likely a small blocker that's obvious in hindsight, that's normal. Keep trying :) 
