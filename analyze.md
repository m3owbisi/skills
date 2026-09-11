/analyze

```markdown
so hello there claude mujko tumhe ek baat batani hai so jo mere yusuf sir heina unko maine apne career aur job ke regarding boht sari baate ki so ive done my bscit in apr 26 aur mera main focus to full mern stack development along with data analysis hi hai leveraging ai aur unko maine ye sab bataya so he came up with ki mere pasme tere liye ek boht convenient kaam hai tu karegi maine bola batao so he said ki unki net tech india ke thane branch mei hi ek aisa insan chaiye jo google flow ya baki ai image video audio generation janta ho editing aati hu thori boht tumko bas unke working instagram page ke liye ai generated content creation karna hai jisme ek thumbnail ho avatar ho uske sequenced frames ke hisab se tumko ek short form content banake dena hai minimum 8 - maximum 60 secs ka unke topic aur script ka use karke aur video alag hoga audio uspe shyd alag ho aur editing ka part along with captions chaiye so maine ek influencer ke free guides boht use karti hu for my own purposes so uske idr muje boht sare content creation ke liye mile hai sab docs mujko bas kal wo lok ek chota sa interview lege uske badme mujko apna pura bada sa system aur credit points dege for an ultimate hour jisme muje unko ek pura wesa reel banake dena hai so what i want from you is that guides mei jitne bhi listed plugins, connectors, skills.. ya kuch aese useful codes aur prompts jo mai use kar saku to please usko yaha list out kardo sari cheeze thike irrespective of a few constraints ill link those reel examples down here its their new concept called job talk.. my sir told me that theyll pay me a good descent amount of the salary also its very easy to travel & commute.
add files, manage connectors, and more
apify : instagram reel scraper
https://www.instagram.com/reel/DdDvobeB-BP/?utm_source=ig_web_copy_link&stkn=MzRlODBiNWFlZA==
https://www.instagram.com/reel/Dc-_WsXuv9C/?utm_source=ig_web_copy_link&stkn=MzRlODBiNWFlZA==
https://www.instagram.com/reel/Dc0ErnFRQzk/?utm_source=ig_web_copy_link&stkn=MzRlODBiNWFlZA==
```
Pulled all three reels via Apify — good news: they're actually all from the brand's own account (@nettechjobtalk, "NetTech Job Talk"), so this checks out as a real, existing page, not a random ask. Here's the teardown, then the full tool list you asked for.

The 3 reels at a glance
Reel Length Plays Likes Topic Hook type CTA						
Dc0ErnFRQzk (3 Sep)	16s	2,039	20	"Who do I even ask about jobs?" (Hindi)	Relatable pain-point question	Follow (in caption only)
Dc-_WsXuv9C (7 Sep)	37s	1,065	5	HR interview traps	Direct callout + myth-bust ("you're already going wrong")	Watch full video, link in bio
DdDvobeB-BP (9 Sep)	39s	1,095	3	Google Data Scientist hiring process	Direct callout + credential flex ("You know Python. You know SQL.")	Comment "DS" → DM

Median plays across these three: 1,095. None of these is a real outlier yet (the 16s one at ~1.9x is the closest) — this is a young page still finding its footing, which is useful context for what you're walking into.

Patterns showing up already:

The two English reels both open by directly calling out the viewer's false confidence ("You think you're good at X" / "You know Python, SQL...") before revealing the gap — that's the account's house hook style.
Shorter + simpler (the 16s Hindi hook-only reel) outperformed the two longer, fuller reels on plays, even with less production. Worth noting for your "8–60 sec" brief — shorter isn't automatically weaker here.
CTA is inconsistent: one relies on caption-only follow bait, one on link-in-bio, one on a comment-keyword DM funnel. The comment-keyword one (video 3) is the most trackable/replicable mechanic.

What this suggests for your niche (AI + careers + tech, Indian freshers): direct-callout hooks that name a specific skill or fear ("You know X, so why aren't you Y") are the account's proven pattern — lean into that for your AI-careers angle rather than a generic "AI is changing hiring" opener.

Everything usable from those guides, organized

Skills you can install (Customize → Skills, works on free plan too):

analyze — the one I just used; reverse-engineers reels/TikToks into hook/structure/retention teardowns, pulls transcripts via Apify automatically.
video-prompt-enhancer — turns a one-line idea into a full 6-part cinematic prompt (subject/action/scene/camera/style/avoid), then can hand off to a connected video generator.
Corey Haines' free marketingskills pack — content-strategy, copywriting, copy-editing, social, ai-seo. Installable in one line via Claude Code (npx skills add coreyhaines31/marketingskills) or manually on web.

Connectors (Customize → Connectors, one-time OAuth, no API keys to paste):

Apify — what I just used. Scrapes Instagram/TikTok reels + transcripts for research/teardowns.
Arcads — takes a rough idea or a finished clip and renders/restyles it (runs Veo 3.1, Sora, Kling, and Google's Omni model for re-editing existing footage with new camera moves/graphics).
Higgsfield — avatar/character-locked video generation (Soul ID face-lock + Seedance for cinematic shots), useful for the "consistent avatar across frames" part of your brief.

External tools mentioned (not Claude-native, used alongside it):

Fish Audio — voice cloning + emotion-tagged TTS ([excited], [whisper] etc.), 83 languages, free tier exists.
CapCut — free editing/captioning, where you'd assemble everything.
Google AI Studio / Nano Banana — for thumbnail compositing.
ChatGPT + the Higgsfield plugin — an alternate route to the same product-video codes if you're not in Claude.

On the "UGC that doesn't look AI" / face-clone material: it's genuinely useful for texture and camera realism, but a couple of those guides are explicitly about making synthetic content indistinguishable from real people without disclosure. For a company page that's putting your face/avatar out as "the brand," it's worth deciding upfront with Yusuf sir whether AI-generated content will be labeled as such — that's a brand-trust and platform-policy question you'll want settled before tomorrow's interview, not after.

Want me to run a deeper teardown on any one of these three reels specifically (full single-video mode, with hook/structure/retention breakdown), or draft the actual demo reel (hook → script → shot list → prompts) for your interview task using the account's proven hook pattern?
..
Got it — that's the ai-seo skill (a.k.a. AEO/GEO): getting content cited by ChatGPT, Perplexity, Google AI Overviews etc. rather than just ranked on Google. It's built for websites/blogs/docs — pricing pages, comparison tables, schema markup, llms.txt — not really for Instagram reels, so it doesn't slot directly into the NetTech Job Talk reel work from earlier.

Since you just dropped the file with no request attached — what do you want to do with it? A couple of guesses, tell me if one's right:

NetTech's own site (if they have one beyond Instagram) — you want to check if it shows up when people ask ChatGPT/Perplexity "best career prep for freshers in India" type questions
Your own portfolio/resume site or blog — making sure it gets surfaced if someone asks an AI "AI + MERN stack developer for hire"
Something else entirely, just wanted it on file for later

NetTech India-Leading IT & non-IT Training Institute in Mumbai, Thane, Navi Mumbai
Deep Web research
