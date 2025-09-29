# Byte Pair Encoding (BPE) — Exercises & Tasks

## Introduction
This repository contains a small, focused set of exercises to implement and explore the Byte Pair Encoding (BPE) algorithm. The goal is hands-on: implement a minimalist BPE, extend it to full training, compare behavior on different corpora, and apply it to a non-Latin script (Urdu).

BPE summary: start with characters as tokens, repeatedly find the most frequent adjacent token pair and merge it into a new token. Repeat for a specified number of merges to build a subword vocabulary.
