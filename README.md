## What is Mossland?
![Title](https://user-images.githubusercontent.com/109493423/196594604-a77066c1-1478-4726-85db-52e0963f9724.png)

Mossland is a blockchain project that began as a metaverse connecting the real and virtual worlds and has grown into infrastructure for the AI civilization. Building on its virtual reality, augmented reality, and NFT-based entertainment roots, Mossland now develops agentic AI governance, AI-driven media, and Physical AI services — all coordinated on-chain through Moss Coin(MOC), which ties the ecosystem into an integrated economic system.

모스랜드(Mossland)는 현실과 가상 세계를 잇는 메타버스에서 출발해, 이제는 AI 문명을 위한 인프라(Infrastructure for the AI Civilization)로 확장하고 있는 블록체인 프로젝트입니다.
VR·AR·NFT 기반 엔터테인먼트 서비스로 쌓아 온 실사용 경험을 토대로, 현재는 에이전트 기반 AI 거버넌스, AI 미디어, 피지컬 AI(Physical AI) 서비스를 개발하고 있습니다. 이 모든 서비스는 모스코인(MOC)을 통해 하나의 통합된 경제 순환 구조로 연결됩니다.

- [moss.land](https://www.moss.land/)
- [X (Twitter)](https://twitter.com/theMossland)
- [GitHub](https://github.com/mossland)
- [Medium Blog](https://medium.com/mossland-blog)

## Projects

### 2026 Alpha
Alpha는 [alpha.moss.land](https://alpha.moss.land)에서 운영되는 크립토 × AI 미디어 + 커뮤니티 서비스입니다. SignalMap 정규화 저장소를 기반으로 한국 유튜브 채널·뉴스·매크로 피드를 수집하여 채널별 stance 분포, AI 합성 데일리 브리프, 검색 가능한 Q&A(RAG), 8명의 공개된 AI 페르소나(7일 자동 정산(CoinGecko 기준) 가격 예측 트랙레코드 포함), 키워드+임베딩 하이브리드 검색을 제공합니다. 12개 도구가 노출된 [MCP 서버](https://github.com/MosslandOpenDevs/alpha-mcp)로 Claude·Cursor·Cline·Continue·Zed에서 직접 호출 가능. 처음부터 인간 독자와 주요 LLM(GPT, Gemini, Perplexity, Claude) 양쪽에 인용되도록 설계되었습니다.

- [Homepage](https://alpha.moss.land/)
- [GitHub](https://github.com/MosslandOpenDevs/alpha)
- [Developers](https://alpha.moss.land/developers)
- [MCP 서버](https://github.com/MosslandOpenDevs/alpha-mcp)
- [Ask Alpha](https://alpha.moss.land/ask)
- [AI 페르소나](https://alpha.moss.land/agents)

### 2026 SignalMap
SignalMap은 한국 유튜브 채널을 중심으로 뉴스·매크로 피드까지 통합하여 자산·토픽·이벤트의 정규화된 저장소를 만드는 멀티 소스 내러티브 파이프라인입니다. xAI Grok(grok-4-fast 계열)으로 영상 1건당 한 번의 호출로 요약·핵심 주장·인용·토픽·입장(stance)을 추출하고, OpenAI 임베딩(text-embedding-3-small)으로 의미 임베딩을 만들어 토픽 네트워크 그래프를 시각화합니다. Alpha 등 후속 제품의 RAG·페르소나·MCP 서버 데이터 소스로 활용됩니다.

- [Homepage](https://signalmap.moss.land/)

### 2026 MOSS.AO (Agentic Orchestrator)
MOSS.AO는 여러 AI 에이전트를 오케스트레이션하여 소프트웨어를 자율적으로 설계·구현하는 오픈소스 엔진(agentic-orchestrator)으로, 모스랜드 피지컬 AI(Physical AI) 생태계를 위한 인프라입니다. 로컬 LLM(Ollama)과 API 기반 모델을 하이브리드로 라우팅하며, 발산(divergence)·수렴(convergence)·계획(planning) 단계를 거치는 다중 에이전트 협업으로 Web3·피지컬 AI 서비스를 발굴하고 구현합니다. [ao.moss.land](https://ao.moss.land/)에서 실시간 파이프라인 대시보드가 운영 중입니다. (MIT 라이선스)

- [Homepage](https://ao.moss.land/)
- [GitHub](https://github.com/MosslandOpenDevs/agentic-orchestrator)

### 2026 Passport
Passport는 모스코인(MOC) 홀더를 위한 자가지갑(self-custody) 활성화·인증 프로그램으로, 모스랜드 거버넌스 스택의 1계층(참여 자격·기록 레이어)에 해당합니다. 자산 이동이나 가스비 없이 서명(signature)만으로 지갑 소유를 확인하고, 월간 체크인 스탬프·투표 위임·시그널 투표 등 거버넌스 참여를 기록합니다. 2026년에 인증한 지갑에는 1회성 'Founding 2026' 스탬프가 발급됩니다(2026년 이후 미발급). 현재 오픈베타로 운영되며, Agora·Algora 등 다른 서비스와는 독립적으로 동작합니다.

- [Homepage (Open Beta)](https://passport.moss.land/)

### 2026 Algora
Algora는 24시간 상시 가동되는 실험적 에이전트 거버넌스 플랫폼으로, 거버넌스 스택의 3계층에 해당합니다. 다수의 AI 에이전트가 로컬(Ollama)·API(OpenAI/Claude) 하이브리드 오케스트레이션으로 크립토 트렌드를 상시 분석·토론하고, 그 결과를 Agora의 사람 투표에 '추천'으로 제안합니다(“AI가 추천하고, 사람이 결정한다”). 실시간 로직 시각화와 커스텀 에이전트 주입을 지원하며, 리스크가 큰 행동은 사람 승인 전까지 잠금됩니다. 현재 실험/PoC 단계로 운영됩니다.

> ※ Agora(구속력 있는 사람 투표 계층)와 Algora(실험적 AI 상시 심의 계층)는 이름이 비슷하지만 서로 다른 프로젝트입니다.

- [Homepage (Experimental)](https://algora.moss.land/)
- [GitHub](https://github.com/MosslandOpenDevs/Algora)

### 2025 MAIT (서비스 종료)
MAIT(Mossland DAO AI Toolkit)은 모스랜드의 DAO 운영 효율을 높이고 의사결정을 자동화하기 위해 AI 기능을 결합한 도구였습니다. 커뮤니티의 제안과 투표 데이터를 실시간으로 분석해 제안 초안 작성, 거버넌스 브리프 생성 등으로 DAO 참여를 돕는 것을 목표로 했습니다.

MAIT 독립 서비스는 종료되었으며, 도메인 `mait.moss.land`는 `agora.moss.land`로 리다이렉트됩니다. MAIT의 AI 제안 초안·브리프 기능 자체는 Agora로 이관되어 남아 있지만, 이 방향을 앞으로 Agora 안에서 계속 발전시킬지는 아직 정해진 계획이 없습니다.

- [가이드북 (아카이브)](https://medium.com/mossland-blog/mait-mossland-dao-ai-toolkit-%EC%A0%95%EC%8B%9D-%EC%98%A4%ED%94%88-89bd4db5083d)

### 2025 Digital Twin
Digital Twin은 실제 물리적 공간을 메타버스와 연결하여 건물, 도시, 시설 등의 구조와 에너지 사용 정보를 실시간으로 모니터링하고 최적화하는 리서치 프로젝트입니다. Autodesk Revit과 Autodesk Tandem 기술을 활용해 3D 모델링 데이터를 메타버스 플랫폼과 연동함으로써 에너지 효율성, 안전 관리 등 새로운 가치를 창출하는 다양한 사용 사례를 연구하고 있습니다. 또한 블록체인 기술을 적용해 데이터 무결성과 투명성을 높여, 미래 지향적인 메타버스 환경을 구축하고자 합니다.

- [GitHub](https://github.com/MosslandOpenDevs/MosslandAI/tree/main/DigitalTwin)

### 2025 Mossland AI
Mossland AI는 AI와 Web3의 접점을 탐구하는 공개 리서치 프로젝트입니다. 2026년 현재 DAO 거버넌스용 AI, 자율 온체인 에이전트, 지속가능한(그린) AI, 디지털 트윈, 스테이블코인, 캐릭터 AI, 블록체인 네트워크 인프라 등 여러 갈래의 연구를 다루며, 모든 연구는 모스코인(MOC)·DAO 거버넌스·메타버스 등 모스랜드 생태계에 기반합니다. 대부분의 문서는 한국어·영어로 함께 공개됩니다.

- [GitHub](https://github.com/MosslandOpenDevs/MosslandAI)

### 2025 Moss Coin (MOC) ERC-20
모스코인(MOC)이 2025년 이더리움 메인넷에 새로운 ERC-20 컨트랙트로 재발행되었습니다. Luniverse 엔터프라이즈 체인에서 이더리움 메인넷으로의 마이그레이션은 온체인 DAO 투표(2025년 7월, 만장일치 찬성)로 승인되었으며, 컨트랙트는 2025년 8월 4일 배포·검증되었습니다. 총 발행량은 500,000,000 MOC로 고정되어 있고, 소유자 없는(ownerless) 구조로 관리자 키가 존재하지 않으며, Burnable·Permit(EIP-2612)·Votes(ERC20Votes) 기능을 갖추고 CertiK 감사를 받았습니다. 발행 물량은 2/3 멀티시그(Gnosis Safe)에 보관됩니다.

- Contract (Ethereum Mainnet): [`0x8bbfe65e31b348cd823c62e02ad8c19a84dd0dab`](https://etherscan.io/token/0x8bbfe65e31b348cd823c62e02ad8c19a84dd0dab)
- [GitHub](https://github.com/mossland/MossCoin-ERC20-2025)
- [CertiK 감사](https://skynet.certik.com/projects/mossland)
- ⚠️ 안내: 공식 채널에서 확인한 위 메인넷 주소만 사용하세요. 구 2018 ERC-20 및 Luniverse MOC는 레거시이며, WMOC 스왑 경로는 종료되었습니다.

### 2024-2025 Agora
Agora는 모스랜드의 DAO 거버넌스 플랫폼으로, 현재 [agora.moss.land](https://agora.moss.land/)에서 프로덕션으로 운영되고 있습니다. 지갑 서명 한 번(EIP-712)으로 가스비 없이 MOC 보유량에 비례해 투표하는 오프체인 투표(스냅샷 블록 기준, 독립적으로 재검증 가능), 제안 라이프사이클, 포럼, SIWE(EIP-4361) 지갑 로그인을 제공합니다. AI가 제안 초안을 작성(Gemini)하고 중립적 거버넌스 브리프를 생성(Claude Opus 4.8)하는 기능이 내장되어 있으며, 이는 종료된 MAIT 서비스의 AI 브리프 기능을 이어받은 것입니다. Agora는 모스랜드 거버넌스 스택의 '구속력 있는 결정 계층'으로, 참여 자격 레이어인 Passport, 실험적 AI 심의 레이어인 Algora와 함께 3계층 구조(Passport → Agora → Algora)를 이룹니다.

- [Homepage](https://agora.moss.land/)
- [GitHub](https://github.com/MosslandOpenDevs/Agora)
- [소개자료](https://medium.com/mossland-blog/%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%95%84%EA%B3%A0%EB%9D%BC-agora-67b3b2e3fa7f)
- [가이드북](https://medium.com/mossland-blog/agora-officially-launched-6cb9ee65a2cf)

### 2022-2023 Mossland Metaverse
모스코인이 활용되는 오픈소스 메타버스 플랫폼입니다. 모스코인의 사용성을 확대하고 더 많은 사용자와 개발자를 모스랜드 생태계로 끌어들이기 위해 개발되었습니다. 사용자들은 아바타로 공간을 이동하며 소통하고, MOC 기반 서비스와 다양한 미니 게임·이벤트에 참여할 수 있습니다.

현재 모스랜드 메타버스는 오픈소스 [WorkAdventure](https://github.com/workadventure/workadventure)를 자체 호스팅(self-hosting)한 [wa.moss.land](https://wa.moss.land/)로 운영되며, 마을·오피스·컨퍼런스 등의 공간 맵을 제공합니다. 맵은 오픈소스로 개발되어 누구나 제안과 기여에 참여할 수 있습니다.

- [Homepage](https://wa.moss.land/)
- [GitHub (WorkAdventure 맵)](https://github.com/MosslandOpenDevs/mossverse-wa-map)
- [GitHub (이전 버전, deprecated)](https://github.com/MosslandOpenDevs/mossverse)
- [소개자료](https://github.com/MosslandOpenDevs/mossverse/raw/main/MosslandMetaverse_ko.pdf)

### 2022-2023 Mossverse Hackathon
모스랜드 메타버스 내의 미니 서비스를 오픈소스 해커톤을 통해 개발하는 프로젝트로 모스랜드 프로젝트 투명성을 강화하고 오픈소스 참여를 활성화하여 모스코인의 사용처를 증가시키는 것을 목적으로 합니다. 이 프로젝트에서는 메타버스 내에 다양한 콘텐츠를 오픈소스로 개발하고 공급하는 것이 목표입니다. 해커톤은 공개된 GitHub Repository에서 진행되며 누구나 아이디어를 제안하고 개발에 참여할 수 있습니다.

- [GitHub - MosslandOpenDevs/Hackathon](https://github.com/MosslandOpenDevs/Hackathon)

### 2022 CyberTHUG Gecko Club
![GeckoClub](https://user-images.githubusercontent.com/109493423/196594010-4834b9ed-0d75-45d4-9ce3-dd1c45e728d4.png)

CyberTHUG Gecko Club(이하 사이버더그 게코 클럽)은 NFT(Non-Fungible Token) 게임으로, 크레스티드 게코 도마뱀을 브리딩하는 과정을 경험할 수 있는 프로젝트입니다. 이 게임은 사이버더그 게코 클럽에서 진행되며, 게코라는 도마뱀 종류 중 하나인 크레스티드 게코를 모티브로 합니다.

사이버더그 게코 클럽은 NFT 게임의 형태로 구현되어 있으며, 블록체인 기술을 통해 게임 아이템의 소유권과 거래가 투명하게 기록됩니다. 이를 통해 참여자들은 게코 모프를 소유하고 거래할 수 있으며, 게임 내에서의 활동을 통해 NFT의 가치를 창출하고 소셜 상호작용을 즐길 수 있는 플랫폼입니다.

- <del>[Homepage](https://gecko.thecyberthug.com/)</del>
- [Guidebook](https://cyberthuggeckoclub.notion.site/CyberTHUG-Gecko-Club-Guidebook-2f5cb5a1b23d4257b75552d3190fdf76)

### 2022 CyberTHUG PFP-NFT
![CyberTHUG](https://user-images.githubusercontent.com/109493423/196594110-e00cd0a4-d79b-44df-8d8b-e792da03fd96.png)

CyberTHUG는 모스랜드에서 시작된 PFP(Profile Picture) NFT 프로젝트입니다. 이 프로젝트는 Decentralized Autonomous Organization(DAO)를 형성하고 있습니다. 이 DAO는 블록체인 기술을 기반으로 한 분산 자율 조직으로, 참여자들이 공동으로 프로젝트의 방향성을 결정하고 운영합니다.

CyberTHUG는 또한 PSA(Public Service Announcement)를 중요하게 여깁니다. PSA는 대중에게 중요한 정보를 전달하고 사회적 이슈를 알리는 역할을 합니다. CyberTHUG는 이러한 PSA를 통해 사회의 모습을 개선하고 사회적인 문제를 인식시키는 데 주력합니다. 이를 통해 참여자들에게 사회적 책임감을 심어주고, 사회적 가치를 높이는데 기여하고자 합니다.

- [Homepage](https://www.thecyberthug.com/)

### 2021 e스포츠 AMX 승부예측
![amx](https://user-images.githubusercontent.com/109493423/196594157-dbd76165-2e88-499a-a5d6-78997de0153e.png)

한국 최초 프로 e스포츠 레이싱 대회 “코오롱 AMX e스포츠 챔피언십”의 승부예측 이벤트를 AMX와 모스랜드가 함께 진행합니다. “코오롱 AMX e스포츠 챔피언십”는 AMX와 주식회사 아프리카 콜로세움이 공동으로 개최하는 e스포츠 레이싱 대회입니다. 2021년 10월 27일, 28일 양일간 이벤트가 진행됩니다.

- <del>[Homepage](https://amx.s999.kr/)</del>
- [Trailer](https://www.youtube.com/watch?v=GvLMefVyoag)
- [AMX](http://amxesports.com/)

### 2021 승부예측 999
![999](https://user-images.githubusercontent.com/109493423/196594145-355d2cf5-5c4e-40a3-9789-61c06acba981.png)

'승부예측 999'는 스포츠 경기 승부를 예측하고 그 결과에 따라 상금을 받는 서비스입니다. 참가자는 매일 제시되는 스포츠 경기 결과를 예측합니다. 예측 결과에 따라 순위가 매겨지고 순위에 따라 매주 모스코인(MOC)을 상금으로 받을 수 있습니다.

'승부예측 999'는 매일 제시되는 스포츠 경기 결과를 예측하고 상금을 받는 서비스로, 프로야구, 프로축구, 리그 오브 레전드, 해외축구 등의 경기에 대한 예측 경쟁이 이루어집니다. 참가자들은 예측 결과에 따라 순위를 받고, 매주 모스코인(MOC)을 상금으로 받을 수 있습니다. 모스랜드는 스포츠를 분석하고 예측하는 것을 스포츠를 더욱 즐길 수 있는 방법으로 제공하고자 하며, 스포츠 데이터와 블록체인 기술을 결합하는 시도로 시작된 프로젝트입니다.

- 2021년 4월 1일 서비스 오픈 ~ 2022년 3월 8일 서비스 종료
- <del>[Google Play](https://play.google.com/store/apps/details?id=com.mossland.s999)</del>
- <del>[Homepage](https://s999.kr/)</del>
- [Trailer](https://www.youtube.com/watch?v=H1-C9yFOY1c)

### 2020 ROYAL MARBLE
![RoyalMarble](https://user-images.githubusercontent.com/109493423/196594250-c1e2a7c7-bd07-4fba-9077-b8ea42d4ba80.png)

로얄마블은 부루마블 매니저 게임으로, 사용자들은 게임 내 건물, 아바타, 주사위 등의 다양한 요소들을 조합하여 다른 사용자와 1:1 대결을 펼칠 수 있습니다. 게임은 캐주얼 수집형 보드 & 매니저 게임으로 분류되며, 현실 세계를 반영한 모노폴리 세계관에서 진행됩니다. 게임의 목적은 카드 수집 및 육성과 상위 랭크 경쟁입니다. 주요 특징으로는 세계적인 테이블탑 게임인 '모노폴리'에 현실 세계의 랜드마크를 접목한 1:1 PvP 게임이 있습니다.

로얄마블은 eSports 대회 운영을 통해 모스코인의 사용처를 발굴합니다. 이를 위해 유료형 대회 컨텐츠인 Mossland League을 도입하고, 대회 참가비와 대회 상금을 모스코인으로 사용할 수 있도록 합니다.

- <del>[Google Play](https://play.google.com/store/apps/details?id=com.realityreflection.mossmarblemanager)</del>
- [Trailer](https://www.youtube.com/watch?v=D0z5kfR-bz0)
- [Gameplay Trailer](https://www.youtube.com/watch?v=FDB3ZWa-_aY)

### 2020 LIGA ROCKET
![LigaRocket](https://user-images.githubusercontent.com/109493423/196594289-ebf55f71-288d-4839-b07f-0c140be83293.png)

'리가 로켓(Liga Rocket)'은 모바일 캐주얼 게임으로서, 지속 가능한 게임 대회(e-Sports)를 위한 대회 플랫폼을 제공합니다. 이 게임은 남녀노소 누구나 손쉽게 즐길 수 있는 캐주얼한 플레이 양식을 갖추고 있으며, 대회에서는 상금이 수여됩니다.

게임은 매일 열리는 대회와 상금 운영을 중심으로 지속 가능한 게임 대회를 제공합니다. 대회 운영은 게임의 핵심 요소이며, 상금 시스템을 통해 경쟁자들의 열정과 참여를 유도합니다. '리가 로켓'은 중독성이 높고 랭킹 경쟁심이 높은 하이퍼캐주얼 게임을 특징으로 합니다.

또한, '리가 로켓'은 디지털자산 상금 시스템을 도입함으로써 국가간 장벽 없이 글로벌 접근이 가능합니다.

- <del>[Google Play](https://play.google.com/store/apps/details?id=com.rr.luckyrocket)</del>
- [Youtube Review #1](https://www.youtube.com/watch?v=_YbXRTrhoyU)
- [Youtube Review #2](https://www.youtube.com/watch?v=0garrEIsapw)

### 2020 GANGSTA UNDERGROUND
![Gangsta-Underground_Poker](https://user-images.githubusercontent.com/109493423/196594298-06275156-16e0-47d7-ab36-b8bca78ba7a9.png)

Gangsta Underground: The Poker은 어두운 뒷골목에서 진행되는 갱스터들의 포커 리그 게임입니다. 이 게임은 현실적이고 갱스터처럼 보이는 캐릭터들과 함께하는 긴장감 넘치는 플레이를 통해 플레이어에게 즐거움과 도전을 제공합니다. 게임은 Unreal Engine 4를 통해 높은 수준의 가상현실(Virtual Reality) 경험을 제공하며, 플레이어들은 현실 세계의 뒷골목에서 포커를 플레이하는 갱스터로서의 역할을 수행합니다.

게임은 블록체인 기술과 NFT(Non-Fungible Token) 디지털 재화를 접목하는 것을 목표로 합니다. 플레이어들은 게임 내에서 획득한 NFT 디지털 재화를 소유하고 거래할 수 있으며, 이를 통해 게임의 경제 시스템과 상호작용할 수 있습니다. 이러한 결합은 블록체인의 투명성과 보안성을 활용하여 게임 내 자산의 소유권과 거래 기록을 보장하고, 플레이어들에게 새로운 경험과 가치를 제공합니다.

Gangsta Underground: The Poker은 가상현실(Virtual Reality)과 블록체인 기술의 융합을 통해 높은 수준의 가상현실 경험 구현을 시도하는 프로젝트입니다.

- [Steam](https://store.steampowered.com/app/689720/Gangsta_Underground__The_Poker/)
- [Trailer](https://www.youtube.com/watch?v=Byga2vszaYo)
- [Gameplay Trailer](https://www.youtube.com/watch?v=SwDmQECNGTc)

### 2019 THE HUNTERS
![Hunters](https://user-images.githubusercontent.com/109493423/196594309-1af99661-9461-4484-91ca-af0def4a1ac0.png)

더 헌터스는 위치기반 게이밍 리워드 앱입니다. 이 앱을 사용하는 사용자들은 주변에 흩어진 가상의 골드를 수집하고, 이 골드를 랜드마크 체크인을 통해 가상의 통화인 모스코인으로 교환할 수 있습니다. 이는 현실 세계의 위치 정보를 기반으로 한 게임적인 요소를 활용하여 사용자들이 재미있게 참여할 수 있는 형태로 구성되어 있습니다.

모스코인은 상품 구매나 개인 월렛으로의 출금 등 다양한 용도로 사용될 수 있습니다. 사용자들은 앱 내에서 모스코인으로 구매 가능한 다양한 상품이나 서비스를 탐색하고 구매할 수 있습니다. 또한, 개인 월렛으로 모스코인을 출금하여 암호화폐로 전환하거나 다른 지갑으로 이체할 수도 있습니다.

- 2019년 5월 20일 서비스 오픈 ~ 2020년 5월 18일 서비스 조기 종료
- Covid-19 대응 활동에 동참하기 위하여 조기 서비스 종료
- [Trailer](https://www.youtube.com/watch?v=wkkjPZlsCL8)
- [Guide video](https://www.youtube.com/watch?v=3vv0suiKr4Q)
- <del>[HNINE](https://www.hnine.com/project/the-hunters-app.html)</del>

### 2018 THE AUCTION
![Auction](https://user-images.githubusercontent.com/109493423/196594319-2373e584-35be-4210-8313-85264949e350.png)

모스랜드 더 옥션은 모스랜드에서 제공하는 경매 서비스로, 가상 랜드마크의 판매를 위한 플랫폼입니다. 이 서비스를 통해 사용자들은 랜드마크의 주인이 되어 롯데월드타워, 에펠탑, 자유의 여신상과 같은 유명한 랜드마크를 소유할 수 있습니다. 모스랜드는 블록체인 시장에서 토큰 거래 이외에도 활용할 수 있는 새로운 영역을 모색하기 위해 옥션 서비스를 개발했습니다.

모스코인은 서비스 내에서 거래에 사용되는 디지털자산으로 거래소보다 서비스 내에서 발생하는 거래량이 많아져 하루에 740만 달러 수준의 거래량을 기록하기도 하였습니다. 이러한 거래량은 모스랜드가 제공하는 블록체인 서비스의 가능성과 잠재력을 보여주는 중요한 지표입니다. 모스랜드 더 옥션을 통해 사용자들은 가상의 랜드마크를 경매를 통해 소유할 수 있으며, 이를 통해 블록체인의 투명하고 안전한 거래 환경을 경험할 수 있습니다.

- 2018년 10월 12일 서비스 오픈 ~ 2020년 2월 26일 서비스 종료
- <del>[Homepage](https://auction.moss.land)</del>
- [Guide video](https://www.youtube.com/watch?v=wySgBhPkfi8)

### 2018 GAME JAM SEOUL
![GameJam](https://user-images.githubusercontent.com/109493423/196594326-3c2c46b9-7667-4120-94ae-26cda8e0104a.png)

모스랜드와 룸네트워크는 블록체인 게임 산업의 발전을 위해 Blockchain Game Jam Seoul을 공동으로 개최했습니다. 이 행사에는 블록체인과 게임에 관심있는 다양한 참가자들이 모여 7개의 팀을 구성하여 3일 동안 게임을 개발하고 다양한 블록체인 기술을 선보였습니다.

모스랜드와 룸네트워크는 이 행사에서 블록체인 게임 개발을 위한 사이드체인을 제공하며, 참가자들이 블록체인 기반 게임을 쉽고 빠르게 개발할 수 있도록 지원했습니다. 약 60명의 개발자, 기획자, 디자이너가 참가하였으며, 우승팀에게는 상금, 암호화폐 모스코인, 후속 개발 지원 등의 혜택이 주어졌습니다.

Blockchain Game Jam Seoul은 블록체인 리서치 그룹인 논스(Nonce) 커뮤니티 공간에서 개최되었으며, 암호화폐 거래소인 고팍스(GOPAX), 프로그래밍 교육 단체 멋쟁이사자처럼(LikeLion), 블록체인 미디어 디센터(Decenter)가 후원하였습니다.

- [Trailer](https://www.youtube.com/watch?v=dXG6vp8MtTU)
- [Press](https://decenter.kr/NewsView/1S3E9SRMYB/GZ03)
