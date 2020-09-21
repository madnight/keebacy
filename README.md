# Keebacy

[Link to website](https://madnight.github.io/keybacy/)

A minimalist typing program inspired by [wpm](https://github.com/cjbassi/wpm-spa) and built for the browser using React, TypeScript, and Redux.
It includes different typing modes such as 'words', 'quote', 'wiki', and 'custom', and gives you typing stats based on the current text being typed.
Quotes were taken from wpm which were taken from http://www.typeracerdata.com/texts.

## Keyboard Shortcuts

| Key   |  Action  |
|---|---|
| Ctrl+Delete  | Deletes the last word |
| Escape  | Retry sample  |
| Tab  | Get a new sample |
| F5  | Reset stats |

# FAQ

#### Q: What's the difference to keybr?

The target audience for [keybr](https://keybr.com) users are beginner touch typist who want to improve their typing accuracy and speed by fixing their weaknesses for individual characters. But keybr has its limits, as soon as you are free of weaknesses (everything green and confidence 1) you will be annoyed by their non-sense words and the lack of different typing modes, also keybr does not have Ctrl+Delete (delete last word) which becomes important at higher speeds. Keebacy improves on keybr in that it replaces non-sense words by word from the [NGSL](https://en.wikipedia.org/wiki/New_General_Service_List) (covering 90% of written english) and adds Ctrl+Delete plus two additional modes: quote and wiki.

#### Q: What's the difference to typeracer?

[Typeracers](https://typeracer.com) is known for its multi player type racing feature. Keebacy does not have a multi player and does not intend to add one. This website is only for training (non-competitive) purposes.

#### Q: What's the difference to 10fastfingers?

[10fastfingers](https://10fastfingers.com) main feature is its typing test, where you type for 60 seconds as fast as you can and get a result. 10fastfingers picks the top 200 or top 1000 most common words, but their top 200 common word list also contain non so common words like "Indian". The [NGSL](https://en.wikipedia.org/wiki/New_General_Service_List) used by keebacy list is much better to train with, since it cover 90% of written english. Also, 10fastfingers does not have a cursor in the text (like typereacer), so you either have to focus on the input text field, but then it's hard to read the next word, or you just read the next word and ignore errors or try to fix errors without looking at it (with mixed results). I think the error handling is better in keebacy since it does not focus on speed or highscore, but on accuracy and also has two additional modes: quotes and wiki.

#### Q: What's the difference to monkey-type?

[mokey-type](https://monkey-type.com) is a great typing website, if you haven't heard of yet go ahead and check it out. The monkey-type quotes are longer and can be a little bit tiring. The words mode is not based on the NGSL and therefore contain either way to less words or (if you pick extended mode) some not so common words. The settings do not include a max. error setting, you can go either perfect or with unlimited errors. Also, monkey-type does not have a wiki mode.

#### Q: Why is it called Keebacy?

Keebacy is a combination of (Kee)p + (Keeb)oard + Accur(acy).

#### Q: What's your target user group?

If you are not able to touch type, then I would recommend you to start with [typingclub](https://typingclub.com) in order to learn touch typing. If you are able to touch type or you have your custom typing system that you're comfortable with and you are below 60 WPM, then I would recommend you to train with [keybr](https://www.keybr.com/), because you most likely have some deficits on certain keys which you can fix with this website. If you have no individual character weaknesses left, then Keebacy is for you.

#### Q: I'm already typing at 100 WPM+ is this website still for me?

Yes, but you might want to consult [Jashe's Comprehensive (Speed)Typing Guide](https://archive.is/dh9Ch)

#### Q: How do you recommend to train typing speed on your website?

Do not focus on speed. You will get faster as your accuracy increases, since accuracy is the single most important aspect of typing. I would recommend you to set a max. Error limit in the settings, one that you are comfortable with. I would mostly train with the words mode. The words mode for the english language is based on [NGSL](https://en.wikipedia.org/wiki/New_General_Service_List) a list of the most frequent english words witch covers 90% of written english. Thus, if you are accurate and fast at this mode, then you are accurate and fast in 90% of written english. In order to also train punctuation, capitalization and non-frequent words, I would go with the quote mode. Since the quotes of the quotes mode are the same that are used in typeracer you have the little side effect that you also increase your typeracer speed.

#### Q: Why are the samples rather short?

Keebacy focuses on burst typing, rather than endurance typing of longer texts. This is because most modern use cases at a computer require you to write one or two sentences, like a chat message answer, short email answer, google search, youtube search and so on. Also, it's not very likely that you can think many sections ahead. It's more likely that you think for while, type, think and so on. If you are more into endurance typing of longer text, then I can recommend you [typelit](https://www.typelit.io/), where you can type entire books like Ulysses with over 1000 pages.

#### Q: What settings do you recommend?

I would recommend to set the maximum amount of errors (Max. Error) setting to 5. This results in a minimum accuracy of at least 96% per sample.


#### Q: Why do you offer only english and german?

I intend to add more langauges, but I want to have a very high level of quality for every mode of them. For the wiki mode it's rather easy, because all there is to change is the API call to get wiki article in other languages. But for quotes and words it is a little bit more complex. I don't want google auto translations or strange words like other typing websites have. Therefore, I need some assistance here. For the words mode I need the top 10k most frequent words of the language, like the [NGSL](https://en.wikipedia.org/wiki/New_General_Service_List) that I use for english. These lists do not always have a high quality. In case of the german list I had to manually filter out many artifacts.
