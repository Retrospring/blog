# Temporarily disabling Languages on Retrospring

If you read this post, you probably either saw the tweet or site announcement on Retrospring about us temporarily disabling language switching/multi-language support, and you may ask why that happens.

<!--more-->

First, let's talk about what's changing in general, for the following weeks:

* The language switcher at the bottom of the page has been removed.
* If you had any non-English locale set, the site will be displayed in English regardless of your setting.
* Attempting to set the language through any means will still leave the language set to English.

### So, why is this happening?

Retrospring has had translation support since 2015, and since that time, we received translations for a multitude of languages, these being:

* German
* French
* Czech
* Italian
* Japanese

(We also had _Pirate English_ and _Gangster English_ as some alternatives available)

Especially with the latter one, Japanese, we noticed issues after we were done localizing the interface. We received feedback from the community translators that the given translations didn't make much sense in the interface, but by that time it already was "too late".

To explain the issue, we'll go into some finer details about the structure of the locales. Let's take the following example:

```
[user] answered your question
```

Now this is a fairly easy thing to translate, but the issue comes up if you start storing the translations in the wrong way.

If we keep the `[user]` part static in the interface and don't include it in the translation, we basically fix the order to always be

```
answered your question
```

after a username.

And this doesn't work in a lot of languages, especially where a subject might be present in a different part of the sentence.

Of course, this can be worked around by translators, but it isn't a particularly fun experience and it doesn't really sound _natural_ either.

----

### _Will this not mess with the people that use Retrospring in a different language?_

It might, and we are sorry for this, but we also checked our numbers and currently, out of almost 11,000 users less than 100 use Retrospring in a language different than English.

----

So that's why we're doing this kind of hard cut. We already removed all non-English locales and currently are in the process of reworking the English one.

Once the English locale is finished, we will a translation platform and the community will be able to help us translate Retrospring into their own languages.

We have no specific date nor timeframe for this, but once everything is ready, we will put out another announcement explaining everything!

We'll hope that this change isn't a too great inconvience for many!