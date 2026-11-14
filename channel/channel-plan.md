# Kids YouTube Channel — Channel Plan

**Channel:** Kahani Ka Jhola | कहानी का झोला — Hindi Kids Stories
**Goal:** Roz 1 animated Hindi kids story video YouTube par. Script se lekar video banane aur posting tak ka saara kaam Claude karega, bina review ke (Ritam ka faisla, 14 Nov 2026).
**Tool:** `kids-cartoon-story` skill (offline engine: rigged cartoon characters, Hindi voices, lip-sync, music, read-along subtitles).

## Format
- **Platform:** YouTube main channel. Instagram sirf emotional flat reels ke liye hai (`flat-story-reel` skill).
- **Main video:** 16:9 (1920×1080), 3–5 minute ka, Hindi narrator ke saath har character ki alag awaaz, read-along subtitles aur music.
- **Roz kitni video:** 1 (abhi Shorts nahi; baad mein jod sakte hain).
- **YouTube settings:** Made for Kids = **Yes**, Category Film & Animation, Public, `isAiGeneratedContent: false` (cartoon animation realistic nahi hai).
- **Posting time:** roz **shaam 6:00 baje IST** (badal sakte hain).

## Branding (ho chuka hai)
- Profile picture: Chiku khargosh aur Kachhu kachhua laal jhole mein (Design canvas: https://claude.ai/artifact/YHAsFhiwyVaY5xZUYW3DEG)
- Channel description aur keywords: chat mein diye gaye (14 Nov 2026)

## Channel cast (har video mein naam aur awaaz same)
| Naam | Character | Swabhav | Awaaz (Kokoro) |
|---|---|---|---|
| Chiku | खरगोश (rabbit) | tez, thoda ghamandi, seekhta hai | hm_psi, speed 1.05, pitch 1.28 |
| Kachhu | कछुआ (tortoise) | dheema, samajhdar | hm_omega, speed .86, pitch .9 |
| Bholu | हाथी (elephant) | bada dil, madadgaar | hm_omega, speed .9, pitch .85 |
| Mintu | बंदर (monkey) | shararati, mazedaar | hm_psi, speed 1.1, pitch 1.3 |
| Sheru | शेर (lion) | jungle ka raja, kabhi gussa | hm_omega, speed .9, pitch .88 |
| Lali | लोमड़ी (fox) | chalak | hf_beta, speed 1.0, pitch 1.1 |
| Kalu | कौआ (bird) | smart, bolne mein tez | hm_psi, speed 1.1, pitch 1.35 |
| Rohan & Pari | बच्चे (boy, girl) | ghar aur school ki kahaniyan | hm_psi pitch 1.3 / hf_beta pitch 1.15 |
| Narrator | — | pyaari "nani" jaisi awaaz | hf_alpha, speed .92 |

## Har video ka dhaancha
1. **Hook (0–5 sec):** title card aur "आज की कहानी है…"
2. **Kahani:** shuruaat → mushkil → 2–3 mod → hal (15–25 scenes)
3. **सीख:** moral wala scene
4. **Outro:** "ऐसी और कहानियों के लिए जुड़े रहिए… कल मिलते हैं एक नई कहानी के साथ!"

## Quality rules (YouTube "mass-produced content" niyam se bachne ke liye)
- Har din nayi kahani aur naye scenes. Ek template copy-paste nahi karna.
- Har kahani mein saaf seekh ho. Koi darr, hinsa ya galat aadat nahi.
- Copyrighted characters bilkul nahi (Chhota Bheem, Motu Patlu, Doraemon, Peppa, Disney…).
- Mix rakhna: Panchatantra, Jataka aur Aesop ki kahaniyan dobara batana, plus original kahaniyan (achhi aadatein, dosti, safety).

## Auto-posting — kaise chalta hai
1. Roz **1:17 PM IST** par scheduled task "Kahani Ka Jhola – roz ki video" cloud mein chalta hai.
2. Woh backlog se agli kahani leta hai, 16:9 video banata hai.
3. Video GitHub repo `09ritamgupta-max/kahani-ka-jhola-videos` (public) ki `videos` branch par jaati hai. Branch mein sirf aaj ki video rehti hai (force-push), taaki jagah na bhare. Link: `https://raw.githubusercontent.com/09ritamgupta-max/kahani-ka-jhola-videos/videos/v/<file>.mp4`
4. Metricool (brand id 8042594, timezone Asia/Calcutta) us link se video copy karke shaam 6 baje YouTube par auto-publish karta hai.
5. Video log update hota hai aur Ritam ko phone par notification jaata hai.

**Status (14 Nov 2026):** ✅ YouTube Metricool se connected · ✅ GitHub video godown ready · ✅ Test private post schedule hua (23:22)

## Tay karna baaki hai
- Shorts daalne hain ya nahi
