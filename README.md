# Awesome AI Watchers

High-signal people to follow on the AI industry: models, chips, memory,
supply chains, policy, and the money behind them. No hype accounts, no
repost-only feeds, no engagement farming. Every entry is an account a human
reads regularly and can explain what it adds.

Seeded from a deal breakdown by @P_Bonnet (see Origin) that broke down who
actually makes money when an AI company gets acquired.

## The List

### jukan05

https://x.com/jukan05

Semiconductor and AI hardware analyst on the Citrini Research team. Publishes
long-form research on Substack as SemiconSam.

What you get: chip supply chain and memory semiconductor news, China AI
policy scoops (multiple Reuters exclusives, including Beijing weighing curbs
on overseas access to China's top models), model intel like GLM-5.x specs
before launch, and first-hand notes from ICML. Skeptical of national AI hype
cycles, and posts sources alongside the news.

### zephyr_z9

https://x.com/zephyr_z9

Independent AI and chips analyst.

What you get: supply chain analysis of the hardware side of AI, built on a
running thesis that memory is becoming the center of the AI stack now that
Nvidia has lost the perf-per-dollar and perf-per-watt crown. Threads on
model training economics (Meta's LLaMA-scale spending versus DeepSeek R1)
and the business reality behind compute buildouts. Data-backed and
consistently skeptical of hype.

### divBy_zero

https://x.com/divBy_zero

Eric Quinnell. Hardware-focused engineer posting deep dives on inference
numerics and accelerator engineering.

What you get: low-precision inference numerics explained at the level of what
the silicon actually does. Recent posts break down the MXFP8 x MXFP4
mixed-precision trick (fp8 weights, fp4 activations, faster than a plain fp8
matmul) and the implementation cost: 2x activation fetches plus a scale
sidecar running concurrently on the fp8 datapath to match native fp4 element
sizes. Also tracks new accelerator silicon like Jalapeno versus VR200 and
evaluates it honestly, crediting good engineering and calling out what is
not trivial.

### QingFengJianZX

https://x.com/QingFengJianZX

Chinese-language semiconductor supply chain news account (display name
Qingfeng Finance News).

What you get: supply chain signals from the China market side: material
shortages and the stocks tied to them. Recent posts cover the ABF substrate
shortage (the laminate used in advanced chip packaging) and a roundup of the
ABF concept stocks. Useful for tracking the packaging materials and substrate
layer of the supply chain, where shortages surface in prices before Western
coverage.

### earnings_guy

https://x.com/earnings_guy

The Earnings Correspondent. Independent account posting earnings coverage
for public companies.

What you get: fast, charted earnings summaries the moment results drop:
$TICKER (Company) #earnings are out, with TradingView charts and the key
numbers. Covers the AI-adjacent names (ASML, IREN, monday.com) alongside the
rest of the market, which makes it a useful filter for the business reality
behind AI capex. Also posts a weekly lookahead of which companies report next.

### trendforce

https://x.com/trendforce

Market intelligence firm founded in 2000, covering semiconductors, memory,
and displays. Corporate account, not an individual analyst.

What you get: the memory price data everyone else quotes. Posts DRAM and NAND
pricing moves, HBM contract price forecasts (another 70-140% up in 2027), and
CSP capex allocation analysis, with links to the full research. Where the
individual analysts on this list give you takes, TrendForce gives you the
numbers underneath.

### xu159411209

https://x.com/xu159411209

Chinese-language semiconductor supply chain analyst posting under the display
name Zhaowen.

What you get: supply chain updates with stock picks attached. Recent posts
cover the materials choke points: high-purity quartz, germanium, and high-end
NdFeB magnets, with mainland export review tightening since late 2025 slowing
Taiwan equipment deliveries by months, per Nikkei Asia. Reads like a sector
research note: what is tightening, who is exposed, which names benefit.

## Origin

### P_Bonnet

https://x.com/P_Bonnet

Reference post: https://x.com/P_Bonnet/status/2092946471989465470

Breaks down who actually makes money in AI deals. The post that seeded this
list: Nvidia acquires Hugging Face for about $12.9bn, with investors sharing
roughly $7.3bn of profit on under $400m invested (about 20x blended) and Lux
Capital the single biggest winner.

## At a glance

| Handle | Focus | Output |
|--------|-------|--------|
| jukan05 | semis, AI hardware, China AI policy | scoops, research memos, conference notes |
| zephyr_z9 | AI and chips, memory, compute economics | analysis threads |
| divBy_zero | inference numerics, mixed-precision matmul, accelerators | technical deep dives |
| QingFengJianZX | chip packaging materials, ABF substrates, concept stocks | market news and stock roundups (Chinese) |
| earnings_guy | earnings coverage across the market, AI-adjacent names included | charted earnings summaries |
| trendforce | memory pricing, HBM, CSP capex | price data and research summaries |
| xu159411209 | materials choke points, export controls | supply chain updates with stock picks (Chinese) |

## Adding to the list

Curated by hand. An account qualifies when it meets all of:

- Original analysis with sources, not reposts or link drops
- A track record: months of consistent output, not one viral thread
- Stable identity, verifiable as a real person or team
- Active: posted within the last month

Exclude: engagement farming, AI-generated content without substance, accounts
that mostly reply to others, and teasers that lead nowhere without the
paywall clearing.

Want to add someone? Open a PR with the handle and a short note on what the
account adds. The criteria above apply.
