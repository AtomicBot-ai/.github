<p align="center">
  <a href="https://atomicbot.ai">
    <img src="https://github.com/AtomicBot-ai/.github/raw/main/assets/logo.png" width="120" alt="Atomic" />
  </a>
</p>

<p align="center">
  <a href="https://atomicagent.io">Website</a> ·
  <a href="https://github.com/AtomicBot-ai/atomic-agent#readme">Docs</a> ·
  <a href="https://discord.gg/Us7qXtDGw">Discord</a> ·
  <a href="https://x.com/atomicagent_io">X</a>
</p>

<p align="center">
  Open-source local AI — agents, chat, and inference. Private by default.
</p>

---

### Atomic Chat

<a href="https://atomic.chat/"><img src="https://img.shields.io/badge/Website-atomic.chat-00B894?style=flat" alt="Website" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/Atomic-Chat?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/Atomic-Chat?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat/graphs/contributors"><img src="https://img.shields.io/github/contributors/AtomicBot-ai/Atomic-Chat?style=flat&logo=github&label=Contributors&color=ff69b4" alt="Contributors" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/Atomic-Chat?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/.github/raw/main/assets/0529_final.gif" width="100%" alt="Atomic Chat" />
</p>

An open-source desktop AI app. Run local LLMs from Hugging Face or connect cloud models (OpenAI, Anthropic, Mistral, Groq, MiniMax, others). Available on macOS, Windows, Linux, iOS, and Android.

#### Download

<p align="left"><b>Desktop</b></p>
<p align="left">
  <a href="https://github.com/AtomicBot-ai/Atomic-Chat/releases/download/v2.0.0/Atomic.Chat_2.0.0_universal.dmg"><img src="https://img.shields.io/badge/macOS-Universal-000000?style=for-the-badge&logo=apple&logoColor=white" height="46" alt="Download for macOS" /></a>&nbsp;
  <a href="https://github.com/AtomicBot-ai/Atomic-Chat/releases/download/v2.0.0/Atomic.Chat_2.0.0_x64-setup.exe"><img src="https://img.shields.io/badge/Windows-x64-0078D4?style=for-the-badge&logo=windows11&logoColor=white" height="46" alt="Download for Windows" /></a>&nbsp;
  <a href="https://github.com/AtomicBot-ai/Atomic-Chat/releases/download/v2.0.0/Atomic.Chat_2.0.0_amd64.AppImage"><img src="https://img.shields.io/badge/Linux-AppImage-FCC624?style=for-the-badge&logo=linux&logoColor=black" height="46" alt="Download for Linux" /></a>
</p>

<p align="left"><b>Mobile</b></p>
<p align="left">
  <a href="https://apps.apple.com/us/app/atomic-chat-private-local-ai/id6761720226"><img src="https://img.shields.io/badge/iOS-App_Store-0D96F6?style=for-the-badge&logo=appstore&logoColor=white" height="46" alt="Download for iOS" /></a>&nbsp;
  <a href="https://play.google.com/store/apps/details?id=chat.atomic.app"><img src="https://img.shields.io/badge/Android-Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white" height="46" alt="Download for Android" /></a>
</p>

#### Local OpenAI-compatible server

```sh
curl http://localhost:1337/v1/chat/completions -d '{
  "model": "llama-3.2-3b-instruct",
  "messages": [{ "role": "user", "content": "Why is the sky blue?" }]
}'
```

#### Highlights

- Run open-weight LLMs (Llama, Gemma, Qwen, Mistral, Phi) from Hugging Face — fully offline
- Connect cloud providers: OpenAI, Anthropic, Mistral, Groq, MiniMax
- One-click agent launch — OpenCode & GitHub Copilot CLI from the Integrations tab
- Artifacts — live preview panel for HTML/CSS/JS
- Faster on Apple Silicon — MLX EAGLE-3, MTP, and TurboQuant KV cache
- MCP integration for agentic capabilities; custom assistants for specialized tasks
- Native iOS & Android apps, not wrappers

#### Follow us

<p align="left">
  <a href="https://x.com/atomic_chat_hq"><img src="https://img.shields.io/badge/X-@atomic__chat__hq-000000?style=for-the-badge&logo=x&logoColor=white" alt="Atomic Chat on X" /></a>&nbsp;
  <a href="https://discord.gg/8wGSsvmg4V"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Atomic Chat on Discord" /></a>&nbsp;
  <a href="https://huggingface.co/AtomicChat"><img src="https://img.shields.io/badge/Hugging%20Face-AtomicChat-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Atomic Chat on Hugging Face" /></a>
</p>

#### Contributors

<p align="left">
  <a href="https://github.com/urmauur"><img src="https://avatars.githubusercontent.com/u/10354610?v=4&s=96" width="48" height="48" alt="urmauur" /></a>
  <a href="https://github.com/hohieuai"><img src="https://avatars.githubusercontent.com/u/150573299?v=4&s=96" width="48" height="48" alt="hohieuai" /></a>
  <a href="https://github.com/Vect0rM"><img src="https://avatars.githubusercontent.com/u/71440932?v=4&s=96" width="48" height="48" alt="Vect0rM" /></a>
  <a href="https://github.com/Vanalite"><img src="https://avatars.githubusercontent.com/u/818645?v=4&s=96" width="48" height="48" alt="Vanalite" /></a>
  <a href="https://github.com/Minh141120"><img src="https://avatars.githubusercontent.com/u/91668012?v=4&s=96" width="48" height="48" alt="Minh141120" /></a>
  <a href="https://github.com/hiento09"><img src="https://avatars.githubusercontent.com/u/136591877?v=4&s=96" width="48" height="48" alt="hiento09" /></a>
  <a href="https://github.com/hahuyhoang411"><img src="https://avatars.githubusercontent.com/u/64120343?v=4&s=96" width="48" height="48" alt="hahuyhoang411" /></a>
  <a href="https://github.com/hiro-v"><img src="https://avatars.githubusercontent.com/u/22463238?v=4&s=96" width="48" height="48" alt="hiro-v" /></a>
  <a href="https://github.com/qnixsynapse"><img src="https://avatars.githubusercontent.com/u/17230826?v=4&s=96" width="48" height="48" alt="qnixsynapse" /></a>
  <a href="https://github.com/namchuai"><img src="https://avatars.githubusercontent.com/u/10397206?v=4&s=96" width="48" height="48" alt="namchuai" /></a>
  <a href="https://github.com/dan-menlo"><img src="https://avatars.githubusercontent.com/u/101145494?v=4&s=96" width="48" height="48" alt="dan-menlo" /></a>
  <a href="https://github.com/freelerobot"><img src="https://avatars.githubusercontent.com/u/69952136?v=4&s=96" width="48" height="48" alt="freelerobot" /></a>
  <a href="https://github.com/ramonpzg"><img src="https://avatars.githubusercontent.com/u/40837339?v=4&s=96" width="48" height="48" alt="ramonpzg" /></a>
  <a href="https://github.com/ux-han"><img src="https://avatars.githubusercontent.com/u/89722390?v=4&s=96" width="48" height="48" alt="ux-han" /></a>
  <a href="https://github.com/aindrajaya"><img src="https://avatars.githubusercontent.com/u/14341691?v=4&s=96" width="48" height="48" alt="aindrajaya" /></a>
  <a href="https://github.com/dinhlongviolin1"><img src="https://avatars.githubusercontent.com/u/45910030?v=4&s=96" width="48" height="48" alt="dinhlongviolin1" /></a>
  <a href="https://github.com/louis-jan"><img src="https://avatars.githubusercontent.com/u/133622055?v=4&s=96" width="48" height="48" alt="louis-jan" /></a>
  <a href="https://github.com/LazyYuuki"><img src="https://avatars.githubusercontent.com/u/34532913?v=4&s=96" width="48" height="48" alt="LazyYuuki" /></a>
  <a href="https://github.com/eckartal"><img src="https://avatars.githubusercontent.com/u/159995642?v=4&s=96" width="48" height="48" alt="eckartal" /></a>
  <a href="https://github.com/Van-QA"><img src="https://avatars.githubusercontent.com/u/64197333?v=4&s=96" width="48" height="48" alt="Van-QA" /></a>
  <a href="https://github.com/david-menloai"><img src="https://avatars.githubusercontent.com/u/196951154?v=4&s=96" width="48" height="48" alt="david-menloai" /></a>
  <a href="https://github.com/gau-nernst"><img src="https://avatars.githubusercontent.com/u/26946864?v=4&s=96" width="48" height="48" alt="gau-nernst" /></a>
  <a href="https://github.com/github-roushan"><img src="https://avatars.githubusercontent.com/u/158602016?v=4&s=96" width="48" height="48" alt="github-roushan" /></a>
  <a href="https://github.com/markmehere"><img src="https://avatars.githubusercontent.com/u/52765023?v=4&s=96" width="48" height="48" alt="markmehere" /></a>
  <a href="https://github.com/tikikun"><img src="https://avatars.githubusercontent.com/u/22268502?v=4&s=96" width="48" height="48" alt="tikikun" /></a>
  <a href="https://github.com/samhvw8"><img src="https://avatars.githubusercontent.com/u/12538214?v=4&s=96" width="48" height="48" alt="samhvw8" /></a>
  <a href="https://github.com/danielcwq"><img src="https://avatars.githubusercontent.com/u/75194564?v=4&s=96" width="48" height="48" alt="danielcwq" /></a>
  <a href="https://github.com/bob-ros2"><img src="https://avatars.githubusercontent.com/u/130362425?v=4&s=96" width="48" height="48" alt="bob-ros2" /></a>
  <a href="https://github.com/dev-miro26"><img src="https://avatars.githubusercontent.com/u/121471669?v=4&s=96" width="48" height="48" alt="dev-miro26" /></a>
  <a href="https://github.com/dtorey-d"><img src="https://avatars.githubusercontent.com/u/225388533?v=4&s=96" width="48" height="48" alt="dtorey-d" /></a>
  <a href="https://github.com/shmutalov"><img src="https://avatars.githubusercontent.com/u/8098898?v=4&s=96" width="48" height="48" alt="shmutalov" /></a>
  <a href="https://github.com/dataCenter430"><img src="https://avatars.githubusercontent.com/u/161712630?v=4&s=96" width="48" height="48" alt="dataCenter430" /></a>
  <a href="https://github.com/drakehere"><img src="https://avatars.githubusercontent.com/u/139204511?v=4&s=96" width="48" height="48" alt="drakehere" /></a>
  <a href="https://github.com/ethanova"><img src="https://avatars.githubusercontent.com/u/1507541?v=4&s=96" width="48" height="48" alt="ethanova" /></a>
  <a href="https://github.com/lugnicca"><img src="https://avatars.githubusercontent.com/u/198289288?v=4&s=96" width="48" height="48" alt="lugnicca" /></a>
  <a href="https://github.com/avb-is-me"><img src="https://avatars.githubusercontent.com/u/104213687?v=4&s=96" width="48" height="48" alt="avb-is-me" /></a>
  <a href="https://github.com/linhtran174"><img src="https://avatars.githubusercontent.com/u/8022780?v=4&s=96" width="48" height="48" alt="linhtran174" /></a>
  <a href="https://github.com/thewulf7"><img src="https://avatars.githubusercontent.com/u/1582808?v=4&s=96" width="48" height="48" alt="thewulf7" /></a>
  <a href="https://github.com/vansangpfiev"><img src="https://avatars.githubusercontent.com/u/15782972?v=4&s=96" width="48" height="48" alt="vansangpfiev" /></a>
  <a href="https://github.com/MaxKoshJob"><img src="https://avatars.githubusercontent.com/u/129305675?v=4&s=96" width="48" height="48" alt="MaxKoshJob" /></a>
  <a href="https://github.com/cmppoon"><img src="https://avatars.githubusercontent.com/u/16539223?v=4&s=96" width="48" height="48" alt="cmppoon" /></a>
  <a href="https://github.com/Ssstars"><img src="https://avatars.githubusercontent.com/u/121910637?v=4&s=96" width="48" height="48" alt="Ssstars" /></a>
  <a href="https://github.com/fredatgithub"><img src="https://avatars.githubusercontent.com/u/6720055?v=4&s=96" width="48" height="48" alt="fredatgithub" /></a>
  <a href="https://github.com/sharunkumar"><img src="https://avatars.githubusercontent.com/u/715417?v=4&s=96" width="48" height="48" alt="sharunkumar" /></a>
  <a href="https://github.com/px100"><img src="https://avatars.githubusercontent.com/u/10860314?v=4&s=96" width="48" height="48" alt="px100" /></a>
  <a href="https://github.com/claytonlin1110"><img src="https://avatars.githubusercontent.com/u/118192227?v=4&s=96" width="48" height="48" alt="claytonlin1110" /></a>
  <a href="https://github.com/atoz96"><img src="https://avatars.githubusercontent.com/u/132365140?v=4&s=96" width="48" height="48" alt="atoz96" /></a>
  <a href="https://github.com/yanalialiuk"><img src="https://avatars.githubusercontent.com/u/193742981?v=4&s=96" width="48" height="48" alt="yanalialiuk" /></a>
  <a href="https://github.com/corevibe555"><img src="https://avatars.githubusercontent.com/u/45244658?v=4&s=96" width="48" height="48" alt="corevibe555" /></a>
  <a href="https://github.com/bxdoan"><img src="https://avatars.githubusercontent.com/u/17973436?v=4&s=96" width="48" height="48" alt="bxdoan" /></a>
  <a href="https://github.com/SuperCowProducts"><img src="https://avatars.githubusercontent.com/u/143343957?v=4&s=96" width="48" height="48" alt="SuperCowProducts" /></a>
  <a href="https://github.com/bytrangle"><img src="https://avatars.githubusercontent.com/u/28924121?v=4&s=96" width="48" height="48" alt="bytrangle" /></a>
  <a href="https://github.com/danyurkin"><img src="https://avatars.githubusercontent.com/u/283456650?v=4&s=96" width="48" height="48" alt="danyurkin" /></a>
  <a href="https://github.com/since-2017-hub"><img src="https://avatars.githubusercontent.com/u/34567183?v=4&s=96" width="48" height="48" alt="since-2017-hub" /></a>
  <a href="https://github.com/DistractionRectangle"><img src="https://avatars.githubusercontent.com/u/48034372?v=4&s=96" width="48" height="48" alt="DistractionRectangle" /></a>
  <a href="https://github.com/gary149"><img src="https://avatars.githubusercontent.com/u/3841370?v=4&s=96" width="48" height="48" alt="gary149" /></a>
  <a href="https://github.com/trilh-dev"><img src="https://avatars.githubusercontent.com/u/54902491?v=4&s=96" width="48" height="48" alt="trilh-dev" /></a>
  <a href="https://github.com/gabrielle-ong"><img src="https://avatars.githubusercontent.com/u/17236572?v=4&s=96" width="48" height="48" alt="gabrielle-ong" /></a>
  <a href="https://github.com/marknguyen1302"><img src="https://avatars.githubusercontent.com/u/170505949?v=4&s=96" width="48" height="48" alt="marknguyen1302" /></a>
  <a href="https://github.com/cuhong"><img src="https://avatars.githubusercontent.com/u/24986225?v=4&s=96" width="48" height="48" alt="cuhong" /></a>
  <a href="https://github.com/mykh-hailo"><img src="https://avatars.githubusercontent.com/u/43426404?v=4&s=96" width="48" height="48" alt="mykh-hailo" /></a>
  <a href="https://github.com/DESU-CLUB"><img src="https://avatars.githubusercontent.com/u/52738837?v=4&s=96" width="48" height="48" alt="DESU-CLUB" /></a>
  <a href="https://github.com/0xgokuz"><img src="https://avatars.githubusercontent.com/u/155065525?v=4&s=96" width="48" height="48" alt="0xgokuz" /></a>
  <a href="https://github.com/new5558"><img src="https://avatars.githubusercontent.com/u/12471844?v=4&s=96" width="48" height="48" alt="new5558" /></a>
  <a href="https://github.com/linuxid10t"><img src="https://avatars.githubusercontent.com/u/29358927?v=4&s=96" width="48" height="48" alt="linuxid10t" /></a>
  <a href="https://github.com/0rzech"><img src="https://avatars.githubusercontent.com/u/1907470?v=4&s=96" width="48" height="48" alt="0rzech" /></a>
  <a href="https://github.com/Kuzmich55"><img src="https://avatars.githubusercontent.com/u/81525287?v=4&s=96" width="48" height="48" alt="Kuzmich55" /></a>
  <a href="https://github.com/Crystora"><img src="https://avatars.githubusercontent.com/u/218712309?v=4&s=96" width="48" height="48" alt="Crystora" /></a>
  <a href="https://github.com/mmngn"><img src="https://avatars.githubusercontent.com/u/34374000?v=4&s=96" width="48" height="48" alt="mmngn" /></a>
  <a href="https://github.com/statxc"><img src="https://avatars.githubusercontent.com/u/181730535?v=4&s=96" width="48" height="48" alt="statxc" /></a>
  <a href="https://github.com/vikram761"><img src="https://avatars.githubusercontent.com/u/119474571?v=4&s=96" width="48" height="48" alt="vikram761" /></a>
  <a href="https://github.com/MrAlaminH"><img src="https://avatars.githubusercontent.com/u/88797912?v=4&s=96" width="48" height="48" alt="MrAlaminH" /></a>
  <a href="https://github.com/Lokimorty"><img src="https://avatars.githubusercontent.com/u/87866997?v=4&s=96" width="48" height="48" alt="Lokimorty" /></a>
  <a href="https://github.com/copyhold"><img src="https://avatars.githubusercontent.com/u/42069?v=4&s=96" width="48" height="48" alt="copyhold" /></a>
  <a href="https://github.com/STRRL"><img src="https://avatars.githubusercontent.com/u/20221408?v=4&s=96" width="48" height="48" alt="STRRL" /></a>
  <a href="https://github.com/Dexterity104"><img src="https://avatars.githubusercontent.com/u/173429049?v=4&s=96" width="48" height="48" alt="Dexterity104" /></a>
  <a href="https://github.com/Gri-ffin"><img src="https://avatars.githubusercontent.com/u/82527700?v=4&s=96" width="48" height="48" alt="Gri-ffin" /></a>
  <a href="https://github.com/QuentinMacheda"><img src="https://avatars.githubusercontent.com/u/69113642?v=4&s=96" width="48" height="48" alt="QuentinMacheda" /></a>
  <a href="https://github.com/eltociear"><img src="https://avatars.githubusercontent.com/u/22633385?v=4&s=96" width="48" height="48" alt="eltociear" /></a>
  <a href="https://github.com/jamesdam"><img src="https://avatars.githubusercontent.com/u/687581?v=4&s=96" width="48" height="48" alt="jamesdam" /></a>
  <a href="https://github.com/locnguyen1986"><img src="https://avatars.githubusercontent.com/u/21600443?v=4&s=96" width="48" height="48" alt="locnguyen1986" /></a>
  <a href="https://github.com/razzeee"><img src="https://avatars.githubusercontent.com/u/5943908?v=4&s=96" width="48" height="48" alt="razzeee" /></a>
  <a href="https://github.com/metaspartan"><img src="https://avatars.githubusercontent.com/u/10162347?v=4&s=96" width="48" height="48" alt="metaspartan" /></a>
  <a href="https://github.com/irfanpena"><img src="https://avatars.githubusercontent.com/u/137022864?v=4&s=96" width="48" height="48" alt="irfanpena" /></a>
  <a href="https://github.com/cs-cat"><img src="https://avatars.githubusercontent.com/u/118669451?v=4&s=96" width="48" height="48" alt="cs-cat" /></a>
  <a href="https://github.com/zwpaper"><img src="https://avatars.githubusercontent.com/u/3764335?v=4&s=96" width="48" height="48" alt="zwpaper" /></a>
  <a href="https://github.com/theproductiveprogrammer"><img src="https://avatars.githubusercontent.com/u/23701634?v=4&s=96" width="48" height="48" alt="theproductiveprogrammer" /></a>
  <a href="https://github.com/Diane0111"><img src="https://avatars.githubusercontent.com/u/141645593?v=4&s=96" width="48" height="48" alt="Diane0111" /></a>
  <a href="https://github.com/GenkaOk"><img src="https://avatars.githubusercontent.com/u/2690324?v=4&s=96" width="48" height="48" alt="GenkaOk" /></a>
  <a href="https://github.com/worthant"><img src="https://avatars.githubusercontent.com/u/43885024?v=4&s=96" width="48" height="48" alt="worthant" /></a>
  <a href="https://github.com/Helloyunho"><img src="https://avatars.githubusercontent.com/u/10192625?v=4&s=96" width="48" height="48" alt="Helloyunho" /></a>
  <a href="https://github.com/janpio"><img src="https://avatars.githubusercontent.com/u/183673?v=4&s=96" width="48" height="48" alt="janpio" /></a>
  <a href="https://github.com/kamal"><img src="https://avatars.githubusercontent.com/u/269?v=4&s=96" width="48" height="48" alt="kamal" /></a>
  <a href="https://github.com/Louis454545"><img src="https://avatars.githubusercontent.com/u/83782422?v=4&s=96" width="48" height="48" alt="Louis454545" /></a>
  <a href="https://github.com/tuananhlai"><img src="https://avatars.githubusercontent.com/u/42168740?v=4&s=96" width="48" height="48" alt="tuananhlai" /></a>
  <a href="https://github.com/MauroDruwel"><img src="https://avatars.githubusercontent.com/u/46003176?v=4&s=96" width="48" height="48" alt="MauroDruwel" /></a>
  <a href="https://github.com/mishrababhishek"><img src="https://avatars.githubusercontent.com/u/99353986?v=4&s=96" width="48" height="48" alt="mishrababhishek" /></a>
  <a href="https://github.com/Realmbird"><img src="https://avatars.githubusercontent.com/u/56459277?v=4&s=96" width="48" height="48" alt="Realmbird" /></a>
  <a href="https://github.com/reneleonhardt"><img src="https://avatars.githubusercontent.com/u/65483435?v=4&s=96" width="48" height="48" alt="reneleonhardt" /></a>
  <a href="https://github.com/RONNCC"><img src="https://avatars.githubusercontent.com/u/1313566?v=4&s=96" width="48" height="48" alt="RONNCC" /></a>
  <a href="https://github.com/SamPatt"><img src="https://avatars.githubusercontent.com/u/6955773?v=4&s=96" width="48" height="48" alt="SamPatt" /></a>
  <a href="https://github.com/mesaugat"><img src="https://avatars.githubusercontent.com/u/4240991?v=4&s=96" width="48" height="48" alt="mesaugat" /></a>
  <a href="https://github.com/0saurabh0"><img src="https://avatars.githubusercontent.com/u/97830220?v=4&s=96" width="48" height="48" alt="0saurabh0" /></a>
  <a href="https://github.com/sesajad"><img src="https://avatars.githubusercontent.com/u/4471030?v=4&s=96" width="48" height="48" alt="sesajad" /></a>
  <a href="https://github.com/sdhrt"><img src="https://avatars.githubusercontent.com/u/96222080?v=4&s=96" width="48" height="48" alt="sdhrt" /></a>
  <a href="https://github.com/lucido-simon"><img src="https://avatars.githubusercontent.com/u/47147996?v=4&s=96" width="48" height="48" alt="lucido-simon" /></a>
  <a href="https://github.com/Haleshot"><img src="https://avatars.githubusercontent.com/u/57552973?v=4&s=96" width="48" height="48" alt="Haleshot" /></a>
  <a href="https://github.com/vabatista"><img src="https://avatars.githubusercontent.com/u/1828654?v=4&s=96" width="48" height="48" alt="vabatista" /></a>
  <a href="https://github.com/volodya-lombrozo"><img src="https://avatars.githubusercontent.com/u/51804353?v=4&s=96" width="48" height="48" alt="volodya-lombrozo" /></a>
  <a href="https://github.com/ynshung"><img src="https://avatars.githubusercontent.com/u/61302840?v=4&s=96" width="48" height="48" alt="ynshung" /></a>
  <a href="https://github.com/cashcon57"><img src="https://avatars.githubusercontent.com/u/24542086?v=4&s=96" width="48" height="48" alt="cashcon57" /></a>
  <a href="https://github.com/ddri"><img src="https://avatars.githubusercontent.com/u/958145?v=4&s=96" width="48" height="48" alt="ddri" /></a>
  <a href="https://github.com/hooray804"><img src="https://avatars.githubusercontent.com/u/249061361?v=4&s=96" width="48" height="48" alt="hooray804" /></a>
  <a href="https://github.com/ldebs"><img src="https://avatars.githubusercontent.com/u/26382594?v=4&s=96" width="48" height="48" alt="ldebs" /></a>
  <a href="https://github.com/oolokioo7"><img src="https://avatars.githubusercontent.com/u/107462209?v=4&s=96" width="48" height="48" alt="oolokioo7" /></a>
  <a href="https://github.com/phoval"><img src="https://avatars.githubusercontent.com/u/89515930?v=4&s=96" width="48" height="48" alt="phoval" /></a>
  <a href="https://github.com/theishangoswami"><img src="https://avatars.githubusercontent.com/u/26306586?v=4&s=96" width="48" height="48" alt="theishangoswami" /></a>
  <a href="https://github.com/utenadev"><img src="https://avatars.githubusercontent.com/u/5269694?v=4&s=96" width="48" height="48" alt="utenadev" /></a>
  <a href="https://github.com/zhhanging"><img src="https://avatars.githubusercontent.com/u/39266588?v=4&s=96" width="48" height="48" alt="zhhanging" /></a>
  <a href="https://github.com/sr-albert"><img src="https://avatars.githubusercontent.com/u/41714564?v=4&s=96" width="48" height="48" alt="sr-albert" /></a>
  <a href="https://github.com/gdmka"><img src="https://avatars.githubusercontent.com/u/1773275?v=4&s=96" width="48" height="48" alt="gdmka" /></a>
  <a href="https://github.com/deining"><img src="https://avatars.githubusercontent.com/u/18169566?v=4&s=96" width="48" height="48" alt="deining" /></a>
  <a href="https://github.com/Angelopgit"><img src="https://avatars.githubusercontent.com/u/102934797?v=4&s=96" width="48" height="48" alt="Angelopgit" /></a>
  <a href="https://github.com/anebot"><img src="https://avatars.githubusercontent.com/u/3480512?v=4&s=96" width="48" height="48" alt="anebot" /></a>
  <a href="https://github.com/AlexFromAtomic"><img src="https://avatars.githubusercontent.com/u/275106994?v=4&s=96" width="48" height="48" alt="AlexFromAtomic" /></a>
  <a href="https://github.com/B0sh"><img src="https://avatars.githubusercontent.com/u/8621792?v=4&s=96" width="48" height="48" alt="B0sh" /></a>
  <a href="https://github.com/chindris-mihai-alexandru"><img src="https://avatars.githubusercontent.com/u/12643176?v=4&s=96" width="48" height="48" alt="chindris-mihai-alexandru" /></a>
  <a href="https://github.com/EndlessLucky"><img src="https://avatars.githubusercontent.com/u/66432853?v=4&s=96" width="48" height="48" alt="EndlessLucky" /></a>
  <a href="https://github.com/mooncool"><img src="https://avatars.githubusercontent.com/u/352887?v=4&s=96" width="48" height="48" alt="mooncool" /></a>
  <a href="https://github.com/Jasper-256"><img src="https://avatars.githubusercontent.com/u/42896286?v=4&s=96" width="48" height="48" alt="Jasper-256" /></a>
  <a href="https://github.com/trunghaiy"><img src="https://avatars.githubusercontent.com/u/568319?v=4&s=96" width="48" height="48" alt="trunghaiy" /></a>
  <a href="https://github.com/niesink"><img src="https://avatars.githubusercontent.com/u/445989?v=4&s=96" width="48" height="48" alt="niesink" /></a>
  <a href="https://github.com/maxx-ukoo"><img src="https://avatars.githubusercontent.com/u/21978232?v=4&s=96" width="48" height="48" alt="maxx-ukoo" /></a>
  <a href="https://github.com/myakura"><img src="https://avatars.githubusercontent.com/u/413984?v=4&s=96" width="48" height="48" alt="myakura" /></a>
  <a href="https://github.com/matthewbcool"><img src="https://avatars.githubusercontent.com/u/4493657?v=4&s=96" width="48" height="48" alt="matthewbcool" /></a>
  <a href="https://github.com/MichalZem"><img src="https://avatars.githubusercontent.com/u/19746328?v=4&s=96" width="48" height="48" alt="MichalZem" /></a>
  <a href="https://github.com/Marco-9456"><img src="https://avatars.githubusercontent.com/u/41828058?v=4&s=96" width="48" height="48" alt="Marco-9456" /></a>
  <a href="https://github.com/eren-karakus0"><img src="https://avatars.githubusercontent.com/u/125828710?v=4&s=96" width="48" height="48" alt="eren-karakus0" /></a>
  <a href="https://github.com/thunhuanh"><img src="https://avatars.githubusercontent.com/u/43697014?v=4&s=96" width="48" height="48" alt="thunhuanh" /></a>
  <a href="https://github.com/Fieldnote-Echo"><img src="https://avatars.githubusercontent.com/u/202828230?v=4&s=96" width="48" height="48" alt="Fieldnote-Echo" /></a>
  <a href="https://github.com/Eruis2579"><img src="https://avatars.githubusercontent.com/u/202545932?v=4&s=96" width="48" height="48" alt="Eruis2579" /></a>
  <a href="https://github.com/akaMrNagar"><img src="https://avatars.githubusercontent.com/u/80568442?v=4&s=96" width="48" height="48" alt="akaMrNagar" /></a>
</p>

---

### Atomic Agent

<a href="https://github.com/AtomicBot-ai/atomic-agent/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/atomic-agent?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-agent/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/atomic-agent?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-agent/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/atomic-agent?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-agent#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/atomic-agent/raw/main/assets/demo.gif" width="100%" alt="Atomic Agent" />
</p>

A local-first AI agent that runs on your machine, with local or cloud models. It drives your browser, reads and edits files, runs approved shell commands, and remembers context across sessions. Runs on our TurboQuant `llama.cpp`, so small quantized models stay useful for long, multi-step work on ordinary hardware.

#### Install

macOS / Linux:

```sh
curl -fsSL https://api.atomicbot.ai/agent-install | sh
```

Windows (PowerShell):

```powershell
irm https://raw.githubusercontent.com/AtomicBot-ai/atomic-agent/main/scripts/install.ps1 | iex
```

#### Run

```sh
atomic-agent
```

#### Capabilities

- System browser via ARIA snapshots, shell, filesystem, documents (PDF/DOCX/XLSX), git, clipboard, HTTP, notifications
- GBNF grammar-constrained tool calls, parallel tool batches, cache-hot prompt prefix, externalized state in SQLite
- Local Markdown skills loaded on demand, FTS5 note recall, durable cron and webhook-triggered tasks
- TUI, CLI, OpenAI-compatible HTTP server, and a Tauri sidecar speaking newline-delimited JSON
- Policy-gated dangerous actions, append-only NDJSON traces with prompt-drift replay

---

### Atomic LLaMA

<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/atomic-llama-cpp-turboquant?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/atomic-llama-cpp-turboquant?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant/commits/master"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/atomic-llama-cpp-turboquant?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/.github/raw/main/assets/atomic%20llama.png" width="100%" alt="Atomic LLaMA" />
</p>

A `llama.cpp` fork with TurboQuant KV cache compression and Gemma 4 MTP speculative decoding. ~30-50% throughput gains on the same hardware, drop-in compatible with upstream tools and GGUF.

#### TurboQuant KV cache

WHT-rotated 2/3/4-bit KV cache with backend-native kernels (Metal `TurboFlash`, CUDA, Vulkan, HIP). `turbo3` is the default — 3-bit, ~4.3× compression vs F16.

```sh
llama-server -m model.gguf -c 32768 -ngl 99 -fa on \
  -ctk turbo3 -ctv turbo3
```

#### Gemma 4 MTP speculative decoding

Pair any `gemma4` target with the official `gemma4_assistant` head — loaded into the target context, no second tokenizer or KV cache. +30-50% short-prompt throughput on Gemma 4 26B-A4B / 31B at 85-88% accept rate. [Pre-built assistant heads on Hugging Face.](https://huggingface.co/collections/AtomicChat/gemma-4-assistant-gguf)

```sh
llama-server -m gemma-4-target.gguf -c 16384 -ngl 99 -ngld 99 -fa on \
  --mtp-head gemma-4-assistant-Q4_K_M.gguf \
  --spec-type mtp --draft-block-size 3
```

#### Also included

- `TQ3_1S` / `TQ4_1S` weight quantization via `llama-quantize` — 25-35% smaller than Q8_0, single-digit % PPL delta
- Regularly synced with `ggml-org/llama.cpp`
- Powers local inference in Atomic Chat and Atomic Agent

---

### Community

<p>
  <a href="https://discord.gg/Us7qXtDGw"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>&nbsp;
  <a href="https://x.com/atomicagent_io"><img src="https://img.shields.io/badge/X-000?style=for-the-badge&logo=x&logoColor=fff" alt="X" /></a>&nbsp;
  <a href="https://www.linkedin.com/company/atomicbot/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=fff" alt="LinkedIn" /></a>
</p>

<sub>© 2026 Atomic · <a href="https://atomicbot.ai">atomicbot.ai</a></sub>
