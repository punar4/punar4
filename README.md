### Punarnava

I build LLM and voice applications that you can measure, with evaluations, tests and safety checks, not just a demo.
Final-year CSE student at BMS College of Engineering, Bengaluru (graduating 2027). Open to SDE and AI engineering roles.

**[AR3](https://github.com/punar4/ar3/tree/paypal)**: decides what to do with a failed UPI, card or PayPal payment (retry, ask the customer, stop, or send to a person) and explains why. A rule table, NVIDIA Nemotron read twice, and 10 safety checks; the model diagnoses, code decides, and it acts only after a person approves.
- 98% correct on 150 labelled UPI and card failures vs 31% for rules alone, with 0 unsafe retries vs 50 for retrying everything
- 94–97% on 31 PayPal sandbox cases, 0 unsafe vs 11; also runs as an MCP tool for AI agents; 74 tests
- [PayPal demo](https://ar3-paypal.onrender.com/) · [UPI and card demo](https://ar3-payments.streamlit.app) · [Video](https://youtu.be/xibzvzKGmOY)
- Built for the Nebius × NVIDIA Global AI Hackathon and the PayPal AI Hackathon

**[MedVoice](https://github.com/punar4/med-voice)**: an elder presses one button, asks about their tablets in spoken Kannada, and hears the answer from their own confirmed prescription. Emergencies are checked first (one-tap 108), and no answer is AI-written.
- 66% → 97% on 38 real voice clips after fixing general bugs, then 12/12 on unseen clips with every emergency caught; 140 tests
- FastAPI, React and TypeScript, Gnani Prisma and Timbre, Postgres, Docker
- [Live demo](https://med-voice-afia.onrender.com/elder/FJ8uBWhh2cVQ5CTUUyPK2Q) · [Video](https://youtu.be/eC4Pf11Z2jo)
- Built solo for the Gnani.ai Great Indian AI Internship Challenge

**Now**
- AR3: a held-out test set built from public error codes, and comparing model providers on the same 150 cases
- MedVoice: reminder calls at dose time, and testing with more voices
- Learning: Building with the Claude API (Anthropic), Agentic AI (NVIDIA × Nebius)

[LinkedIn](https://www.linkedin.com/in/punarnavaviswanath4) · [Email](mailto:punarnava4@gmail.com)
