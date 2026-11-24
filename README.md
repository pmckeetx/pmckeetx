# Peter McKee

**I build production AI systems: realtime voice agents, autonomous agent platforms, and (because I can't help myself) a Redis-compatible database in Rust.**

Three decades of shipping software, from dell.com engineering to leading developer relations at Docker, JFrog, Sonar and AssemblyAI. These days I write the code myself again.

[petermckee.dev](https://petermckee.dev) · [Blog](https://petermckee.dev/blog) · [Resume](https://petermckee.dev/resume) · [hello@petermckee.dev](mailto:hello@petermckee.dev)

### What I'm working on

- **[ShrikeDB](https://github.com/shrikedb/shrikedb)**: a Redis-compatible in-memory database in Rust. One shared-nothing shard per core, no locks on the hot path, and a Dash-style extendible hash table so resizing never stalls the keyspace. Point any Redis client at it. ([How the hash table works](https://petermckee.dev/blog/building-shrikedb-extendible-hashing))
- **Realtime voice agents**: guides and runnable examples for PolyAI's Dialog-RSN-1, covering barge-in, voice-to-voice latency, outbound calls that wait on hold, and LangChain, LiveKit and Pipecat integrations. ([Examples](https://github.com/polyai/dialog-rsn-1-examples))
- **Ronin AI**: my consultancy. Multi-tenant voice receptionists grounded in RAG, and agent platforms that swap between Anthropic, OpenAI and Ollama without a rewrite.

### Latest writing

<!-- BLOG-POST-LIST:START -->
- [Connect a phone number to a Dialog-RSN-1 voice agent with Twilio and Python](https://petermckee.dev/blog/connect-a-phone-number-to-a-dialog-rsn-1-voice-agent) · <sub>Nov 25, 2026</sub>
- [Measure barge-in stop time from a stereo call recording in Python](https://dev.to/pmckeetx/measure-barge-in-stop-time-from-a-stereo-call-recording-in-python-4pk0) · <sub>Nov 18, 2026</sub>
- [Start and end a voice agent call in Python without clipping a word](https://dev.to/pmckeetx/start-and-end-a-voice-agent-call-in-python-without-clipping-a-word-330i) · <sub>Nov 12, 2026</sub>
- [Build an outbound voice agent that waits on hold](https://petermckee.dev/blog/build-an-outbound-voice-agent-that-waits-on-hold) · <sub>Nov 2, 2026</sub>
- [Handle barge-in without your voice agent repeating itself](https://petermckee.dev/blog/handle-barge-in-without-your-voice-agent-repeating-itself) · <sub>Oct 29, 2026</sub>

<!-- BLOG-POST-LIST:END -->

[All posts →](https://petermckee.dev/blog) · [RSS](https://petermckee.dev/rss.xml)

### Talks & videos

- ▶️ [How to Get Started with Docker](https://www.youtube.com/watch?v=iqqDU2crIEQ): DockerCon 2020, 430K+ views and still a go-to first stop for learning containers
- ▶️ [Docker Build: Containerizing a React.js Application](https://www.youtube.com/watch?v=8VHheCkw-7k): Docker YouTube
- 🎙️ [Docker for Python Developers](https://talkpython.fm/episodes/show/308/docker-for-python-developers-2021-edition): Talk Python To Me #308
- 🎤 [Continuous Previews with Infrastructure as Code](https://www.pulumi.com/resources/continuous-previews-infrastructure-as-code/): Pulumi Cloud Engineering Summit 2021
- 🎙️ [Leveraging AI for Secure DevOps](https://testguild.com/podcast/performance/p158-peter/): Test Guild

50+ articles, talks and interviews on [petermckee.dev/publications](https://petermckee.dev/publications).

### Before this

Head of Developer Relations & Community at **Docker**, where I hosted the Docker Build show, ran DockerCon and rebuilt the Docker Captains program. Then developer advocacy and community leadership at **JFrog**, **Sonar** and **AssemblyAI**. Before DevRel, I managed the team that re-architected docs.docker.com and Docker's support sites, and spent eight years engineering dell.com.

**Stack these days:** Rust + Tokio · TypeScript / Next.js · Python · PostgreSQL + pgvector · Anthropic, OpenAI, Ollama
