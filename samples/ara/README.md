Bitext - Arabic Lexical Data Resource Sample
============================================

Overview
--------
This directory contains a sample of our [Modern Standard Arabic (MSA) Lexical Data Resource](https://www.bitext.com/arabic-lexical-data/).

Contents
--------
The file [ara-lxd-sample-10k.tsv](ara-lxd-sample-10k.tsv) contains a sample of our MSA Lexical Data Resource covering the top 10,000 most frequent words appearing in Bitext's own corpus (which contains over 5B tokens and is well-balanced with respect to text typology, texts sources and verticals). These 10,000 words cover approximately 65% of our corpus.

The file is in Tabbed-Separated Values (TSV) format, and has the following columns:
- form: the word form itself as it appears in the corpus
- lemma: the corresponding lemma (the canonical dictionary form)
- POS: adjective, adverb, conjunction, noun, numeral, preposition, pronoun, verb
- voice: active, passive (only for verbal forms)
- tense: past, non-past (only for verbal forms)
- mood: indicative, imperative, subjunctive, jussive (only for verbal forms)
- number: singular, dual, plural
- person: 1, 2, 3 (only for verbal forms)
- gender: feminine, masculine
- case: nominative, genitive, accusative (only for nouns, adjectives and some verbal forms)
- state: indefinite, definite, construct
- possessive-number: singular, dual, plural
- possessive-person: 1, 2, 3
- possessive-gender: masculine, feminine

(c) Bitext Innovations, 2023
