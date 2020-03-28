# About

This repository contains a list of the 10000 most common English words, as determined by n-gram frequency analysis of the Google's Trillion Word Corpus.

# Swear-free lists

There are two additional lists which are identical to the original 10,000 word list, but with swear words removed. These are ideal for generating URLs, temporary passwords, or other uses where swear words may not be desired.

# Swears were removed based on these lists:

* reimertz/curse-words
* MauriceButler/badwords
* LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words

# Word length lists

Three of the lists (all based on the US english list) are based on word length:

* Short: 1-4 characters
* Medium: 5-8 characters
* Long: 9+ characters

Each list retains the original list sorting (by frequency, decending).

# Usage

This repo is useful as a corpus for typing training programs. According to analysis of the Oxford English Corpus, the 7,000 most common English lemmas account for approximately 90% of usage, so a 10,000 word training corpus is more than sufficient for practical training applications.

To use this list as a training corpus in Amphetype, paste the contents into the "Lesson Generator" tab with the following settings:

> Make **3** copies of the list
>
> Divide into sublists of size **3**
>
> Add to sources as **google-10000-english**

In the "Sources" tab, you should see google-10000-english available for training. Set WPM at 10 more than your current average, set accuracy to 98%, and you're set to train.

Enjoy!
