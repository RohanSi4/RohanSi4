# hey, i'm rohan

CS at UVA (May 2027), machine learning engineer intern at Expedia Group this summer.
I work on recommender systems and the data pipelines behind them, mostly for things I
actually want to use.

**right now**

- building [Marathon Prep Bot](https://rohansingh04.com/projects/marathon-prep-bot):
  an LLM writes my training plans and is not allowed to compute anything. A TypeScript
  pipeline decodes Garmin FIT binaries, CRC-validates them, and owns every number, with
  243 tests across 32 suites that fail the build when the model and the pipeline
  disagree. Richmond, November 2026.
- I wrote about how it works:
  [my marathon coach is a chat window](https://rohansingh04.com/notes/llm-marathon-coach)

**things I've made**

- [Shortlist](https://movie-reccomender-system-red.vercel.app): a two-tower retriever
  over 89,585 movies behind a Go API. 84.1% HitRate@10 against 73.8% for a popularity
  baseline, measured on 7,060 cold users held out by a global time cutoff and scored
  exactly once ([code](https://github.com/RohanSi4/movie-recommender-shortlist))
- [Signal](https://signal-recommender.vercel.app): Spotify revoked the endpoints this
  was originally built on, so I rebuilt discovery on artist collaboration graphs using
  what the API still supports. Every pick explains its real connection
  ([code](https://github.com/RohanSi4/spotify-recommender-signal))
- [Today](https://health-recap.vercel.app): the SwiftUI training app I use every
  morning. Weight logging, strength tracking with a live muscle map, and coach plans,
  synced with AES-256-GCM where the decryption key never leaves the phone
  ([code](https://github.com/RohanSi4/today-fitness-ios))
- [rohansingh04.com](https://rohansingh04.com): the site everything lives on, a project
  in its own right ([code](https://github.com/RohanSi4/rohansingh04.com))

**find me**: [rohansingh04.com](https://rohansingh04.com) · [linkedin](https://linkedin.com/in/rohansingh4) · rohan.singh04@outlook.com
