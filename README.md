<img src="banana-logo.png" alt="Banana Suite logo" width="64">

# Banana Suite

Tools for running a wiki, chatting with local models, and maintaining their code.
Started by [Luca Zani (OverloadedTech)](https://github.com/OverloadedTech). BananaWiki is maintained by Luca and Officina Tecnologica; BananaChat and BananaVibe are developed at Officina Tecnologica.

- [BananaWiki](https://github.com/BananaSuite/BananaWiki): team documentation, with standalone and hosted installations.
- [BananaChat](https://github.com/BananaSuite/BananaChat): chat with models on your own infrastructure.
- [BananaVibe](https://github.com/BananaSuite/BananaVibe): quick feature trials and maintenance for the other two, submitted as draft pull requests for review.

## How the three fit together

BananaWiki came first. Luca Zani started it alone on 20 February 2026, when
Canalescuola needed a wiki for the Officina Tecnologica project. Work sped up
in June during an FSL placement (formazione scuola-lavoro), and it grew into a
wiki that also runs as a hosting platform.

BananaChat began as BananaAI, out of wanting to self-host AI models. It lives
in its own repository instead of inside the wiki, and exists to introduce
people to a language model running on their own machine. BananaVibe, first
called BananaAgent, is there to try out features quickly and keep up with the
routine maintenance the other two generate. It starts from an issue a
maintainer opens and stops at a draft pull request, so a person still reads
everything before it merges.

All three were internal until September 2026 and are free software now.
BananaWiki's hosted service runs the same code anyone can install, and it is
open to the public at some times and not at others.

Each repository starts at a single commit. They were developed privately
first, and the internal history runs to thousands of commits holding
deployment credentials, tokens and infrastructure notes written for
maintainers only. There is no reliable way to scrub all of that out, so each
public repository begins from a clean export of the current source. Each
one's `NOTICE` records the original start date and first commit.

Source and issue trackers live in the [BananaSuite organization](https://github.com/BananaSuite).
