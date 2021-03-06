## Are you suffering from overexerted spleen? Ask your doctor if Sanilidolochol® is right for you!

# Drug Names

Python program to generate pharmaceutical advertisements for fictional drugs

Drug names based on a Markov chain fed by this [list of drug names](https://druginfo.nlm.nih.gov/drugportal/drug/names/a)

## to use:

set up your virtualenv with Python 3

```python
$ virtualenv -p=(which python3) hm
$ source hm/bin/activate
```

install the requirements

`$ pip install -r requirements.text`



use `drug_name.create_drug_name` to get a medication name, or `generate_advertisement.get_ad` for a full advertisement.

### testing

After activating your virtual env and installing requirements, run

```
$ pytest
```

### other info

You could regenerate names.txt (list of real drug names) or chain.p if you wanted to, but you don't have to.

Don't forget to check out the official drug_names [twitterbot!](https://twitter.com/askyrdoctorabot)

Like our twitterbot?  Learn to set up your own [here.](https://dev.to/emcain/how-to-set-up-a-twitter-bot-with-python-and-heroku-1n39)

You can run any of the files containing if __name__ == '__main__', including:

 -  [drug_name.py](https://github.com/EMCain/drug_names/blob/b6c5563945014a5cad72e37f1aee5e934c094c2f/drug_name.py)

 -  [generate_advertisement.py](https://github.com/EMCain/drug_names/blob/b6c5563945014a5cad72e37f1aee5e934c094c2f/generate_advertisement.py)

 -  [generate_disease.py](https://github.com/EMCain/drug_names/blob/b6c5563945014a5cad72e37f1aee5e934c094c2f/generate_disease.py)

from the command line to print the results.


## Example ads
Are you plagued by restless elbow? Ask your doctor if Mencardand Ethroarb® is right for you!

You don't have to deal with an excess of desert sand bile alone. Ask your doctor if Relermin Azidoline Bexxer Syne Statethine® is right for you!

Are you suffering from pompous knee? Try Sodiumate Hyamiham®!

Is compulsive nausea keeping you up at night? Try Colybate®!

Worried you might have vulgar buttock? Try Priomine®!

Are you suffering from restless intestine? Ask your doctor if Urizol® is right for you!

Are you plagued by sarcastic cornea? Salim Carostidexivenamicavush® can help!

Is excessive exhaustion keeping you up at night? Ask your doctor about Zesynt Suprin Vitripipyra® today!

Worried you might have restless brainstem? Try Therol Estchin®!

Are you plagued by above-average ringing in the ears? Try TaryPenativer HCline®!

You don't have to deal with an excess of taupe bile alone. Try Nuccine®!

## Example medications

Disaline Pricartax

Oluocine

Difil

Sodone Mal Heparideraletolex

Eque

Rotinavirosin

Pratec

Visalcin

Roxia-Duranupra-1a

Lope

Flol

Hydro

Kalorate

Diane

Estralinid

Zaglitone Benofuviriumaccar

Methalfateride

IIII 123

Ferix

Bis

# References

[How to Write a Twitter Bot with Python and Tweepy](https://dototot.com/how-to-write-a-twitter-bot-with-python-and-tweepy)

[How to Fake a Sophisticated Knowledge of Wine with Markov Chains](http://www.onthelambda.com/2014/02/20/how-to-fake-a-sophisticated-knowledge-of-wine-with-markov-chains/)
