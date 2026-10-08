# RHCSA Batch 1: Meta Ads Build Sheet (8 to 15 Oct 2026)

Brand: Sombhabona Learning and Innovation Hub
Prepared: Thu 8 Oct 2026 by ads-expert. All times are Asia/Dhaka (UTC+6).
Source of truth: output/rhcsa-campaign-plan.md (section 5 handoff, post copy 1A, 2B, 5A, 5B, 6B, 7B, 8A, 8B, overview, owner checklist), brand/rhcsa-batch.md, brand/brand-guide.md, brand/faq.md.

> HONESTY NOTE: This is the brand's first paid campaign, and there is no past performance data. Every benchmark below is an indicative planning range, not a forecast. At roughly 2 to 2.70 USD a day, results will be small. The ads support organic posting and WhatsApp follow-up; they will not fill 15 seats on their own. No enrolment numbers are promised.

---

## 0. Summary, and what I changed from the plan (and why)

**Kept exactly as planned:** a 20 USD total for this burst; three stages (A: Launch, B: Proof / risk removal, C: Retargeting / countdown); the per-stage totals (A 8 USD, B 4 USD, C 8 USD); the posts the plan says to boost; the cold and retargeting audiences; messaging (WhatsApp) as the conversion point.

**Changes, each driven by a concrete problem:**

| # | Problem found | Change |
|---|---|---|
| 1 | **The creatives don't exist when the ad sets start.** 5A goes up Mon 12 Oct at 1 PM and 5B at 9 PM, but ad set B starts 12 Oct. 7B goes up Wed 14 Oct at 9 PM, but ad set C starts 13 Oct. 8A goes up at 9 AM on the deadline day itself. Meta ad review can take anywhere from minutes to about 24 hours, so a boost created at 9 AM on 15 Oct might not run before the 5 PM class. | Ad set A boosts the existing posts as planned (1A is live today; 2B is added on 9 Oct). For **B and C**, build the ads **in advance in Ads Manager**, using the same creative files and condensed plan copy, so they are reviewed and scheduled before they're needed. The organic posts still go out on the plan's schedule. Trade-off: likes and comments on these ads won't add to the organic post's counts. That's an acceptable cost for a hard deadline. |
| 2 | **Swapping creatives by hand in one ad set on the deadline day** (7B, then 8A, then Batch 2 after 5 PM) is risky. Every new ad goes back into review, and someone has to be online at exactly the right time. | Ad set C becomes **4 back-to-back retargeting ad sets** (C1 to C4) with the same audience. Each has its own lifetime budget and start/end time. They never run at the same time, so the budget is not split. The total is still 8 USD. The switch to Batch 2 at 5 PM on 15 Oct happens automatically. |
| 3 | The plan asks for "Dhaka city plus a 15 km radius around Mirpur, weighted higher". **Meta can't weight locations**, and stacking city plus radius just duplicates the area. | Use a single **drop pin at 756 West Sewrapara, Mirpur, with a 15 km radius**. That covers most of Dhaka city (including Uttara, Gulshan, Dhanmondi and Motijheel) without any duplication. |
| 4 | The plan's Calls option for C may not be available in Bangladesh, and adding it would split the budget. | WhatsApp only. People can also call from the WhatsApp chat or call 01835350647 directly, which is printed in every ad. |

**Total: A 8.00 + B 4.00 + C1 2.50 + C2 2.50 + C3 2.25 + C4 0.75 = 20.00 USD.** The Batch 2 push (15 USD, 16 Oct to 1 Nov) and the reserve (5 USD) are not part of this sheet.

---

## 1. Campaign-level settings (apply to all ad sets)

| Setting | Value | Why |
|---|---|---|
| Campaign name | `RHCSA_B1_Burst_Oct26_WA` (one campaign; ad sets A, B, C1 to C4) | Easy to filter and report on. |
| Objective | **Engagement**. Conversion location: **Messaging apps, WhatsApp**. | The plan says enquiries convert on WhatsApp. This works without a Pixel. A "messaging conversation started" happens far more often than a form submission, so Meta gets more signal from a tiny budget. Also, a 9,900 BDT in-person course is usually sold in a conversation, not on a form. |
| Performance goal (optimization event) | **Maximize number of conversations** (messaging conversations started) | The closest event to an enquiry that is still frequent enough to optimize on. |
| Budget type | **Ad set lifetime budgets** (not Advantage+ campaign budget) | Lifetime budgets keep each stage to its exact USD amount and allow the fixed start/end times that C1 to C4 rely on. |
| Bid strategy | Highest volume (no cap) | A bid cap or cost cap would stop delivery at these budgets. |
| Attribution | Default | Reporting only. |
| Special Ad Category | **None declared** (see below) | |
| Ad account | **Check that the time zone is Asia/Dhaka.** If it isn't, convert every schedule time below into the account's time zone. | Schedules run on the ad account's time zone, not the Page's. |

**Fallback if WhatsApp isn't connected by launch:** use objective **Traffic** with performance goal **Link clicks** (Landing page views needs a Pixel), CTA **Sign Up**, and the website URL from the UTM table in section 6. Keep the same audiences, copy and budgets.

### Special Ad Category: Employment does not apply here (with one caveat)
- Meta's Employment category covers ads for job opportunities. Third-party summaries of Meta's policy also list "professional certification programs" and guaranteed interviews or placements. These ads are for a **training course**, they offer no job, and they never promise employment or placement ("job support" only, with no guarantee).
- Meta enforces the special-category targeting restrictions based on **where the audience is**, mainly the United States, Canada and parts of Europe. These ads target Dhaka only.
- **Recommendation:** don't declare a Special Ad Category. Keep the copy clearly about education: no job offers, no "get hired" or "job guarantee", no salary figures. **Caveat:** if Ads Manager asks you to declare it, or rejects an ad for this reason, declare Employment and resubmit. Doing that removes the age and radius controls and most detailed targeting, so tell ads-expert and the audience will be rebuilt around the location only. I couldn't find Meta's official text listing the covered countries, so please check the prompt Ads Manager shows you.

### Placements (manual, every ad set)
Include: Facebook Feed, Instagram Feed, Facebook Reels, Instagram Reels, Facebook Stories, Instagram Stories, Instagram Explore.
Exclude: Audience Network, Messenger (inbox and Stories), right column, Marketplace, search results, in-stream video, Threads.
Why: these are the plan's feed and Reels placements, plus Stories, because the plan already makes Story versions of the seat updates and countdowns. Audience Network and the right column usually bring accidental, low-quality clicks and almost never start real WhatsApp conversations.
Asset customization: use the 4:5 version for feeds and a 9:16 version for Stories and Reels. Keep important text out of the top and bottom 14% of 9:16 frames.

### Ad copy rules applied to every ad (from the plan)
- Every ad that mentions the fee also says the exam voucher is not included. Wherever "certificate" or "Red Hat" could be misread, the ad says it is an institute certificate, not the Red Hat certification.
- "Red Hat" appears in text only, to describe the exam. **No Red Hat logo, and no certification badge images** unless the owner confirms permission (plan, owner checklist).
- No testimonials, student results, pass rates, salary figures or job guarantees. Seat counts appear only as **[X]**, filled with the TRUE count on the day. They are never rounded down.
- No personal-attribute phrasing (for example "Are you unemployed?" or "Are you a struggling student?"). Audience descriptions are written in the third person ("Built for CSE/IT students...").
- Urgency is always real: genuine dates, the genuine 15-seat cap, a genuine 5 PM start time.

---

## 2. Audiences

### 2.1 Cold audience (ad sets A and B)

| Field | Setting |
|---|---|
| Audience mode | Click **"Switch to original audience options"** if Ads Manager offers it, so the interests act as real targeting. If only Advantage+ audience is available, set **minimum age 18 and the location as hard controls**, and enter the age range 18 to 40 and the interests below as "audience suggestions". |
| Location | Drop pin: **756 West Sewrapara, Mirpur, Dhaka**, **+15 km** radius. Select "People living in or recently in this location". |
| Age | 18 to 40 |
| Gender | All |
| Language | **Leave blank.** Many Bangla speakers in Dhaka use Facebook in English, so selecting "Bengali" would exclude them. The bilingual copy covers both groups. |
| Detailed targeting | One combined OR group (interests are added together, not narrowed against each other). Meta's interest list changes often, so **search for each term below and add whatever exists today**. |
| Exclusions | People who sent a message to the Page in the last 30 days, and the enrolled-students customer list (if uploaded; see 2.2). From ad set B onward, also exclude the retargeting audience in 2.2, so cold money reaches new people. |

**Detailed targeting: search for these terms**
- **Interests:** Linux, Red Hat, Red Hat Enterprise Linux, CentOS, Fedora, Ubuntu, System administrator, Computer network, Cloud computing, Amazon Web Services, Microsoft Azure, Google Cloud Platform, DevOps, Kubernetes, Docker, Ansible, Computer science, Information technology, Software engineering, Cisco Certified Network Associate (CCNA), CompTIA.
- **Demographics > Education > Field of study:** Computer Science, Computer Engineering, Computer Science and Engineering, Information Technology, Electrical and Electronic Engineering, Software Engineering.
- **Demographics > Education > Schools (optional, Dhaka universities with CSE/IT intake):** Bangladesh University of Business and Technology (BUBT, in Mirpur), Military Institute of Science and Technology (MIST, in Mirpur), Daffodil International University, United International University, American International University-Bangladesh, North South University, BRAC University, East West University, Independent University Bangladesh, Ahsanullah University of Science and Technology, BUET, University of Dhaka.
- **Demographics > Education level:** In college / In undergrad, College grad (this stands in for the plan's "students" and "fresh graduates"; no behaviour exists for "recent graduate").
- **Demographics > Work > Job titles:** System Administrator, System Engineer, Network Engineer, Network Administrator, Linux Administrator, DevOps Engineer, Software Engineer, IT Officer / IT Executive, Support Engineer, NOC Engineer.
- **Industries (optional):** IT and technical services; Computation and mathematics.
- Don't target competitor brands (AT Computer, Linux Patshala). They are rarely available as interests, and using them is poor practice.
- **Sizing check:** the estimated audience should be somewhere between the low hundreds of thousands and about 1 million. If Ads Manager says it is "too narrow", remove the Schools list first.

**Lookalikes:** not for this burst. There is no qualified source yet (Meta needs at least 100 people from one country, and quality is poor below about 1,000). For the Batch 2 push: once 100 or more people have messaged or engaged, create a **1% Bangladesh lookalike** of "people who messaged the Page plus video viewers (50%)", and then limit it with the same Mirpur 15 km pin in the ad set.

### 2.2 Retargeting audience (ad sets C1 to C4; reused for the Batch 2 push)

Create these as custom audiences (Audiences > Create > Custom audience). Use **"Engaged but not enrolled" = Include (any of) minus Exclude**.

| Include (any of) | Source in Ads Manager | Window |
|---|---|---|
| Facebook Page engagers | Facebook Page > "Everyone who engaged with this Page" | 30 days |
| Instagram engagers | Instagram account > "Everyone who engaged with this professional account" | 30 days |
| Video viewers 50%+ | Video > "People who have viewed at least 50%" > select the 2B demo reel and the 5A instructor reel (add 7B once it exists, for the Batch 2 push) | 30 days |
| Messaging contacts | Facebook Page > "People who sent a message to this Page". If Ads Manager offers a WhatsApp / "Messaged your business" source, include it too. | 30 days |
| Website visitors (only if the Pixel is installed; owner to confirm) | Website > All website visitors to skills.sombhabona.org (or URL contains `linux_info`) | 30 days |

| Exclude | Source | Note |
|---|---|---|
| Enrolled students | Customer list (phone numbers in +880 format) | **Only with the students' consent.** Update it daily from 12 Oct. |
| Form submitters | Pixel "Lead" event, or URL contains the form's thank-you page | Only if the Pixel tracks submissions. |

Location: the same Mirpur 15 km pin. Age 18 to 40. Language blank. No detailed targeting (it would shrink an already small pool).

**Size risk (important):** this is a new account, so the retargeting pool may be small by 13 Oct. Meta needs roughly 100 or more matched people to deliver at all, and frequency climbs fast below about 1,000.
- On **Sun 11 Oct**, check the audience size. If it shows "below 1,000", widen the Page and IG engagement windows to **365 days** and add "People who follow or like your Page".
- If it is still under about 500, change C1 to C3 to **retargeting + cold**: duplicate the cold audience from 2.1 into the same ad set's audience as a second "include" set. Meta will favour the warm users anyway.

---

## 3. Ad sets and ads

Shared WhatsApp settings for every ad: **WhatsApp number 01835350647** (connected to the Page). Use a **pre-filled message containing the ad code**, as shown under each ad, so every chat can be traced back to its ad. Log the code in the enquiry sheet next to "Where did you hear about us?".

Formats used below:
- Headline ≤ 40 characters.
- Description is short; it shows mainly in Facebook Feed.
- "Plan copy" means the exact text from rhcsa-campaign-plan.md, section 3.
- UTM links appear in the ad text. They are clickable on Facebook; on Instagram the text link isn't clickable, so the WhatsApp button does the work there.

---

### AD SET A: Launch / awareness (cold)

| Field | Setting |
|---|---|
| Name | `A_Launch_Cold_Mirpur15km` |
| Schedule | Start **Thu 8 Oct, as soon as post 1A is live and the ad is approved (aim for 4:00 PM)**. End **Sun 11 Oct, 11:59 PM**. |
| Budget | **8.00 USD lifetime** (about 2.35 USD/day across about 3.4 days) |
| Audience | Cold audience (2.1) |
| Ads | A1 and A2 from launch. A3 is added Fri 9 Oct, about 9:30 PM, after post 2B is published. |

**Ad A1: boost the existing post 1A (Launch announcement, English first)**
- Build: Ad > "Use existing post" > select the 1A Facebook post (bilingual EN + BN in one post, as the plan specifies).
- **Primary text:** the published plan copy for 1A, Facebook EN plus BN (plan section 3, Post 1A). It can't be edited when you use an existing post. It already includes the voucher disclaimer.
- Headline: `RHCSA (RHEL 9) Batch 1: 15 Oct` (30 chars). Alternative: `First class free: Thu 15 Oct, 5 PM` (34)
- Description: `9,900 BDT | Exam voucher not incl.`
- CTA: **Send WhatsApp Message**
- Pre-filled message: `Hi, I'd like details on RHCSA Batch 1 (A1)`
- Destination: WhatsApp 01835350647. The text links in the post are the plan's plain links (not UTM-tagged). That's acceptable because WhatsApp is the tracked goal.
- Creative: 1A single image, 1080x1350 (plan visual brief: terminal-style background, ~~18,000~~ 9,900 BDT, "45% OFF, Batches 1 & 2 only", "7 DAYS TO GO"). Add a 1080x1920 Story crop for Stories and Reels. No Red Hat logo.

**Ad A2: new ad, Bangla first and short (same 1A image)**
- Build: Ad > Create ad > Single image > upload the 1A image. Write the primary text with the Bangla block first, then `———`, then the English block.
- **Primary text (BN):**
  > মিরপুরে সরাসরি ক্লাসে RHCSA (RHEL 9 | EX200) প্রস্তুতি, একজন কর্মরত Senior Site Reliability Engineer-এর সাথে, আসল RHEL 9 সিস্টেমে।
  >
  > ব্যাচ ১: প্রথম ক্লাস বৃহস্পতিবার ১৫ অক্টোবর, বিকেল ৫:০০–৭:০০ (ফ্রি ডেমো), এরপর প্রতি শুক্র ও শনি বিকেল ৫:০০–৭:০০।
  > - ৩ মাসে ২৫টি ক্লাস, প্রতিটি ক্লাসে হ্যান্ডস-অন ল্যাব
  > - টাইমড চেকপয়েন্ট ও ২টি পূর্ণাঙ্গ মক এক্সাম
  > - লঞ্চ ফি ৯,৯০০ টাকা (নিয়মিত ১৮,০০০ টাকা, ৪৫% ছাড়, শুধু ব্যাচ ১ ও ২)
  > - প্রতি ব্যাচে মাত্র ১৫টি সিট
  >
  > দ্রষ্টব্য: Red Hat exam voucher ফি-তে অন্তর্ভুক্ত নয়। সার্টিফিকেটটি আমাদের প্রতিষ্ঠানের, Red Hat-এর অফিশিয়াল সার্টিফিকেশন নয়।
  > প্রশ্ন থাকলে WhatsApp করুন। ভর্তি: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=a2_launch_bn
- **Primary text (EN, below the divider):**
  > RHCSA (RHEL 9 | EX200) exam prep, in person in Mirpur, with a working Senior Site Reliability Engineer, on real RHEL 9 systems.
  >
  > Batch 1: first class Thu 15 Oct, 5:00 to 7:00 PM (free demo), then every Fri & Sat, 5:00 to 7:00 PM.
  > - 25 classes over 3 months, a hands-on lab in every class
  > - A timed checkpoint and 2 full mock exams
  > - Launch fee 9,900 BDT (regular 18,000 BDT, 45% off, Batches 1 & 2 only)
  > - Only 15 seats per batch
  >
  > Please note: the Red Hat exam voucher is not included. The certificate is our institute certificate, not the official Red Hat certification.
  > Questions? Tap to WhatsApp. Enroll: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=a2_launch_bn
- Headline (BN): `RHCSA ব্যাচ ১ শুরু ১৫ অক্টোবর` | Headline (EN alternative): `RHCSA Prep in Mirpur: 9,900 BDT` (31)
- Description: `প্রথম ক্লাস ফ্রি | ১৫টি সিট`
- CTA: **Send WhatsApp Message**. Pre-filled message: `RHCSA ব্যাচ ১ সম্পর্কে জানতে চাই (A2)`
- Creative: the 1A image (identical to A1, so the only variable being tested is the copy language and length).

**Ad A3: boost the existing post 2B (Free demo reel). Add Fri 9 Oct, about 9:30 PM.**
- **Prerequisite (open item in the plan):** confirm whether non-enrolled people can attend the demo, whether they must register first, and whether attendance is capped. If this isn't confirmed by Fri evening, **don't add A3**. Run A1 and A2 only.
- Build: Ad > Use existing post > the 2B Facebook Reel/video post.
- **Primary text:** the published plan copy for 2B, EN plus BN (plan section 3, Post 2B), with "[owner to confirm the demo registration process]" replaced by the confirmed process. **Add the voucher line before publishing**, because 2B mentions the fee in the video but not the disclaimer in the text. EN: "The Red Hat exam voucher is not included." BN: "Red Hat exam voucher ফি-তে অন্তর্ভুক্ত নয়।"
- Headline: `Try the first RHCSA class free` (29). BN alternative: `প্রথম ক্লাস ফ্রি: ১৫ অক্টোবর`
- Description: `Thu 15 Oct, 5–7 PM | Mirpur`
- CTA: **Send WhatsApp Message**. Pre-filled message: `I'd like to book the free RHCSA demo class (A3)`
- Creative: the 2B reel, 30 to 40 s, 9:16, Bangla speech with burned-in English subtitles (plan script). The first 3 seconds must carry the hook text "Not sure if RHCSA is for you? Try the first class free." Use a 4:5 crop for feeds.

**What A tests**
1. **Copy language and length: A1 (English first, long, existing post) vs A2 (Bangla first, short).** The image is the same, so the copy is the only difference. The winner's language order is then used for B and C.
2. **Format:** image (A1/A2) vs reel (A3). This only gives a direction, because A3 starts about 30 hours later.

**Decision rule for A** (check Sat 10 Oct, 9:00 PM, after about 2 days and about 4 USD spent):
- If one ad has **3 or more conversations** and the other has **0 conversations after 1.50 USD or more spent**, pause the weaker one.
- If both have spent 1.50 USD or more and one's cost per conversation is **at least 2x** the other's, pause the more expensive one.
- If both have fewer than 3 conversations, **don't pause either**. The data is too thin. Compare link CTR and the share of comments asking about fee or schedule, and **keep the plan's default (English first)** for B and C unless A2 is clearly ahead.
- A3 reel: if the hook rate (3-second plays ÷ impressions) is below 15% after 1,000 impressions, re-cut the first 3 seconds before the reel is reused in the Batch 2 push.
- Meta doesn't split the budget evenly between ads in an ad set. If one ad gets under 20% of spend by Sat evening, judge it on its cost per conversation, not its total volume.

---

### AD SET B: Proof / risk removal (cold)

| Field | Setting |
|---|---|
| Name | `B_ProofRisk_Cold_Mirpur15km` |
| Schedule | Start **Mon 12 Oct, 12:00 AM**. End **Tue 13 Oct, 11:59 PM**. **Build and submit by Sat 10 Oct, 9 PM** so the ads are approved before they start. |
| Budget | **4.00 USD lifetime** (2.00 USD/day) |
| Audience | Cold audience (2.1), **excluding** the retargeting audience (2.2) |
| Ads | B1 and B2, new ads using the 5A and 5B creative files. The organic posts still go out on the plan's schedule. |

Put the language blocks in the order that won in A (English first by default). Both blocks go in one primary text, separated by `———`.

**Ad B1: instructor demo reel (5A creative)**
- **Primary text (EN):**
  > Forgot the root password on a RHEL 9 server? Watch our instructor, Senior SRE Md Nazmul Alam, recover it step by step.
  >
  > This is how every class in our RHCSA Exam Ready Course works: a live demo, then you do it yourself in the lab. 25 classes, a timed checkpoint and 2 full mock exams.
  >
  > Batch 1: first class (free demo) Thu 15 Oct, 5:00 to 7:00 PM, Mirpur, then Fri & Sat. Fee 9,900 BDT (45% off, Batches 1 & 2 only). Exam voucher not included.
  > WhatsApp us, or enroll: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=b1_root_reel
- **Primary text (BN):**
  > RHEL 9 সার্ভারের root password ভুলে গেছেন? ধাপে ধাপে কীভাবে রিকভার করতে হয়, দেখাচ্ছেন আমাদের ইন্সট্রাক্টর, Senior SRE মো. নাজমুল আলম।
  >
  > আমাদের RHCSA Exam Ready Course-এর প্রতিটি ক্লাস এভাবেই চলে: আগে লাইভ ডেমো, তারপর ল্যাবে নিজে করা। ২৫টি ক্লাস, টাইমড চেকপয়েন্ট ও ২টি পূর্ণাঙ্গ মক এক্সাম।
  >
  > ব্যাচ ১: প্রথম ক্লাস (ফ্রি ডেমো) বৃহস্পতিবার ১৫ অক্টোবর, বিকেল ৫:০০–৭:০০, মিরপুর, এরপর শুক্র ও শনি। ফি ৯,৯০০ টাকা (৪৫% ছাড়, শুধু ব্যাচ ১ ও ২)। Exam voucher অন্তর্ভুক্ত নয়।
  > WhatsApp করুন, অথবা ভর্তি: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=b1_root_reel
- Headline: `Watch: root password reset on RHEL 9` (36). BN alternative: `লাইভ ডেমো: RHEL 9 root password রিকভারি`
- Description: `Learn it hands-on | Batch 1: 15 Oct`
- CTA: **Send WhatsApp Message**. Pre-filled message: `Hi, I saw the RHCSA demo video (B1)`
- Creative: the 5A reel, 45 to 60 s, screen recording plus face-cam, large EN/BN captions. Hook text in the first 3 seconds. **Syllabus-level skills only, no real exam content** (EX200 is under an NDA). End card: "We practise this live in class | Batch 1: 15 Oct | skills.sombhabona.org | 01835350647". **The file must be ready by Sat 10 Oct.**

**Ad B2: risk-free enrolment (5B creative)**
- **Primary text (EN):**
  > Two ways we make RHCSA enrolment low-risk:
  > 1. The first class is a free demo: Thu 15 Oct, 5:00 to 7:00 PM, in Mirpur.
  > 2. If you enrol and decide it's not for you, you get a full refund within 3 days of the first class.
  >
  > See the instructor, the lab and the teaching style before you commit. Fee 9,900 BDT (regular 18,000 BDT, 45% off, Batches 1 & 2 only). Red Hat exam voucher not included.
  > Batch 1 full? Batch 2 starts Sun 1 Nov, 7:15 to 9:00 PM, at the same launch fee.
  > Enroll: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=b2_riskfree
- **Primary text (BN):**
  > RHCSA-তে ভর্তি ঝুঁকিমুক্ত, দুইভাবে:
  > ১. প্রথম ক্লাস ফ্রি ডেমো: বৃহস্পতিবার ১৫ অক্টোবর, বিকেল ৫:০০–৭:০০, মিরপুর।
  > ২. ভর্তি হওয়ার পর কোর্সটি আপনার জন্য না মনে হলে প্রথম ক্লাসের ৩ দিনের মধ্যে সম্পূর্ণ টাকা ফেরত।
  >
  > সিদ্ধান্ত নেওয়ার আগে ইন্সট্রাক্টর, ল্যাব ও পড়ানোর ধরন নিজে দেখে নিন। ফি ৯,৯০০ টাকা (নিয়মিত ১৮,০০০ টাকা, ৪৫% ছাড়, শুধু ব্যাচ ১ ও ২)। Red Hat exam voucher অন্তর্ভুক্ত নয়।
  > ব্যাচ ১ পূর্ণ হলে? ব্যাচ ২ শুরু রবিবার ১ নভেম্বর, সন্ধ্যা ৭:১৫–রাত ৯:০০, একই লঞ্চ ফি।
  > ভর্তি: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=b2_riskfree
- Headline: `Risk-free: free class + 3-day refund` (36). BN alternative: `প্রথম ক্লাস ফ্রি, ৩ দিনে রিফান্ড`
- Description: `RHCSA (RHEL 9) | 9,900 BDT`
- CTA: **Send WhatsApp Message**. Pre-filled message: `Hi, I'd like to know about the free first class and refund (B2)`
- Creative: the 5B image, 1080x1350 (plan brief: two large icons, "FIRST CLASS FREE" and "FULL REFUND WITHIN 3 DAYS OF FIRST CLASS", plus "RHCSA (RHEL 9) | 9,900 BDT | Batch 1: Thu 15 Oct, 5 PM"). Add a 1080x1920 Story version.

**What B tests:** proof (watching the instructor work) vs risk removal (free class plus refund), on a cold audience.
**Decision rule** (check Tue 13 Oct, 2:00 PM, after about 38 hours and about 3 USD spent): pause an ad only if it has spent **1.50 USD or more with 0 conversations** while the other has **2 or more**. Otherwise let both run to the end. Whichever message wins becomes the lead angle for the Batch 2 cold ads.

---

### AD SET C: Retargeting / countdown, as 4 back-to-back ad sets (C1 to C4)

All four use the retargeting audience (2.2), the same placements and WhatsApp settings, and never run at the same time.
**Build C1, C2, C3 and C4-A on Sun 11 Oct and submit them**, so they are approved well before they start. Build the **[X] seat-count variants** on the morning of each day using the real count (see the rule below).

| Ad set | Name | Start | End | Lifetime budget |
|---|---|---|---|---|
| C1 | `C1_Retarget_StillDeciding` | Tue 13 Oct, 12:00 AM | Tue 13 Oct, 11:59 PM | 2.50 USD |
| C2 | `C2_Retarget_Tomorrow` | Wed 14 Oct, 12:00 AM | Wed 14 Oct, 11:59 PM | 2.50 USD |
| C3 | `C3_Retarget_Today` | Thu 15 Oct, 12:00 AM | Thu 15 Oct, 4:30 PM | 2.25 USD |
| C4 | `C4_Retarget_Batch2Bridge` | Thu 15 Oct, 5:00 PM | Thu 15 Oct, 11:59 PM | 0.75 USD |
| | | | **Total C** | **8.00 USD** (same as the plan) |

If Ads Manager rejects a budget as below its minimum for the length of the schedule, add C4's 0.75 USD to C3 and simply change C3's ad to the C4 ad at 5 PM.

**Seat-count rule [X]:** each C ad set has one **evergreen** ad (no number) and one **[X] seats left** ad.
- Build the [X] ad on that morning, before 9 AM, using the **TRUE** count. Never round it down. If the true count doesn't feel urgent (for example 14 of 15), don't build the [X] ad; the evergreen ad runs alone.
- If the count changes during the day, edit the number. The edit sends the ad back to review, but the evergreen ad keeps delivering in the meantime.
- If Batch 1 fills, **pause every Batch 1 ad immediately** and move C4's start time to "now" (see section 4).

**C1: "Still deciding?" (Tue 13 Oct)**

*Ad C1-A, evergreen (5B image): the plan's retargeting message*
- EN:
  > Still deciding on RHCSA? The first class is free: Thu 15 Oct, 5:00 to 7:00 PM, at 756 (3rd floor), West Sewrapara, Mirpur. And if you enrol and change your mind, there's a full refund within 3 days of the first class.
  >
  > Fee 9,900 BDT (45% off, Batches 1 & 2 only). Red Hat exam voucher not included. Seats are confirmed in order of enrolment.
  > Batch 1 full? Batch 2 starts Sun 1 Nov, 7:15 to 9:00 PM.
  > WhatsApp us for the live seat count, or enroll: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c1a_still_deciding
- BN:
  > RHCSA নিয়ে এখনো ভাবছেন? প্রথম ক্লাস ফ্রি: বৃহস্পতিবার ১৫ অক্টোবর, বিকেল ৫:০০–৭:০০, ৭৫৬ (৩য় তলা), পশ্চিম সেওড়াপাড়া, মিরপুর। আর ভর্তির পর মত বদলালে প্রথম ক্লাসের ৩ দিনের মধ্যে সম্পূর্ণ রিফান্ড।
  >
  > ফি ৯,৯০০ টাকা (৪৫% ছাড়, শুধু ব্যাচ ১ ও ২)। Red Hat exam voucher অন্তর্ভুক্ত নয়। ভর্তির ক্রম অনুযায়ী সিট নিশ্চিত হয়।
  > ব্যাচ ১ পূর্ণ হলে? ব্যাচ ২ শুরু রবিবার ১ নভেম্বর, সন্ধ্যা ৭:১৫–রাত ৯:০০।
  > সিটের সর্বশেষ তথ্য জানতে WhatsApp করুন, অথবা ভর্তি: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c1a_still_deciding
- Headline: `Still deciding? First class is free` (35). BN alternative: `এখনো ভাবছেন? প্রথম ক্লাস ফ্রি`
- Description: `Full refund within 3 days`
- CTA: **Send WhatsApp Message**. Pre-filled message: `Hi, I have a question about RHCSA Batch 1 (C1A)`

*Ad C1-B, seat count (6B image, built on the morning of 13 Oct)*
- EN:
  > 2 days to go: [X] seats left in RHCSA Batch 1. First class (free demo) this Thursday, 15 Oct, 5:00 to 7:00 PM, Mirpur. Fee 9,900 BDT (45% off). Exam voucher not included.
  > Can't make the 5 PM slot? Batch 2 starts Sun 1 Nov, 7:15 to 9:00 PM, same fee, instructor and syllabus.
  > Enroll: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c1b_seats
- BN:
  > আর মাত্র ২ দিন: RHCSA ব্যাচ ১-এ আর [X]টি সিট বাকি। প্রথম ক্লাস (ফ্রি ডেমো) এই বৃহস্পতিবার, ১৫ অক্টোবর, বিকেল ৫:০০–৭:০০, মিরপুর। ফি ৯,৯০০ টাকা (৪৫% ছাড়)। Exam voucher অন্তর্ভুক্ত নয়।
  > বিকেল ৫টায় সুবিধা না হলে? ব্যাচ ২ শুরু রবিবার ১ নভেম্বর, সন্ধ্যা ৭:১৫–রাত ৯:০০, একই ফি, ইন্সট্রাক্টর ও সিলেবাস।
  > ভর্তি: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c1b_seats
- Headline: `[X] seats left in RHCSA Batch 1` (≤ 32). Description: `First class Thu 15 Oct, 5 PM`
- CTA: **Send WhatsApp Message**. Pre-filled message: `Is there still a seat in RHCSA Batch 1? (C1B)`
- Creative: the 6B image ("2 DAYS LEFT | [X] SEATS LEFT IN BATCH 1", plus a smaller line "Next: Batch 2, Sun 1 Nov, 7:15 PM"), with the true number.

**C2: "Tomorrow, 5 PM" (Wed 14 Oct)**

*Ad C2-A, evergreen (7B creative)*
- EN:
  > Tomorrow at 5:00 PM, RHCSA Batch 1 begins, and the first class is a free demo. Come to 756 (3rd floor), West Sewrapara, Mirpur, meet Senior SRE Md Nazmul Alam, and start your RHEL 9 / EX200 preparation.
  >
  > Fee 9,900 BDT (45% off) | Full refund within 3 days of the first class | Exam voucher not included.
  > Batch 1 full? Batch 2 starts Sun 1 Nov, 7:15 to 9:00 PM.
  > Message us to confirm your seat: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c2a_tomorrow
- BN:
  > আগামীকাল বিকেল ৫:০০টায় শুরু হচ্ছে RHCSA ব্যাচ ১, প্রথম ক্লাস ফ্রি ডেমো। চলে আসুন ৭৫৬ (৩য় তলা), পশ্চিম সেওড়াপাড়া, মিরপুরে। Senior SRE মো. নাজমুল আলমের সাথে পরিচিত হোন, আর শুরু করুন আপনার RHEL 9 / EX200 প্রস্তুতি।
  >
  > ফি ৯,৯০০ টাকা (৪৫% ছাড়) | প্রথম ক্লাসের ৩ দিনের মধ্যে সম্পূর্ণ রিফান্ড | Exam voucher অন্তর্ভুক্ত নয়।
  > ব্যাচ ১ পূর্ণ হলে? ব্যাচ ২ শুরু রবিবার ১ নভেম্বর, সন্ধ্যা ৭:১৫–রাত ৯:০০।
  > সিট কনফার্ম করতে মেসেজ করুন: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c2a_tomorrow
- Headline: `RHCSA Batch 1 starts tomorrow, 5 PM` (35). BN alternative: `আগামীকাল বিকেল ৫টায় ব্যাচ ১ শুরু`
- Description: `First class free | Mirpur`
- CTA: **Send WhatsApp Message**. Pre-filled message: `I'd like to join tomorrow's RHCSA class (C2A)`
- Creative: the 7B reel, 15 to 20 s (lab lights on, RHEL 9 terminal, an empty seat; text "TOMORROW | 5:00 PM | RHCSA Batch 1 begins | First class FREE"). **For the pre-built ad, use a version without "[X] seats left" burned into the video.** If the reel isn't ready by Sun 11 Oct, use a single 1080x1350 image with the same text.

*Ad C2-B, seat count (built on the morning of 14 Oct):* the same text as C2-A, with the first line changed to "Tomorrow at 5:00 PM, RHCSA Batch 1 begins. [X] seats left." / "আগামীকাল বিকেল ৫:০০টায় শুরু RHCSA ব্যাচ ১। আর [X]টি সিট বাকি।"
- Headline: `Tomorrow 5 PM: [X] seats left`
- Pre-filled message: `(C2B)`
- UTM: `utm_content=c2b_seats`
- Creative: a 7B image with the true number.

**C3: "Today, 5 PM" (Thu 15 Oct, until 4:30 PM)**

*Ad C3-A, last call (8A creative)*
- EN:
  > LAST CALL: RHCSA Batch 1 starts TODAY at 5:00 PM, at 756 (3rd floor), West Sewrapara, Mirpur. The first class is free: walk in, meet the instructor, and see the RHEL 9 lab.
  >
  > The quickest way to secure a seat today: WhatsApp or call 01835350647 and we'll confirm right away.
  > Fee 9,900 BDT (45% off) | Full refund within 3 days of the first class | Exam voucher not included.
  > Enroll: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c3a_today
- BN:
  > শেষ সুযোগ: RHCSA ব্যাচ ১ শুরু আজ বিকেল ৫:০০টায়, ৭৫৬ (৩য় তলা), পশ্চিম সেওড়াপাড়া, মিরপুর। প্রথম ক্লাস ফ্রি: চলে আসুন, ইন্সট্রাক্টরের সাথে পরিচিত হোন, RHEL 9 ল্যাব দেখুন।
  >
  > আজই সিট নিশ্চিত করার সবচেয়ে দ্রুত উপায়: WhatsApp বা কল করুন 01835350647, আমরা সাথে সাথে কনফার্ম করব।
  > ফি ৯,৯০০ টাকা (৪৫% ছাড়) | প্রথম ক্লাসের ৩ দিনের মধ্যে সম্পূর্ণ রিফান্ড | Exam voucher অন্তর্ভুক্ত নয়।
  > ভর্তি: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c3a_today
- Headline: `Batch 1 starts TODAY, 5 PM, Mirpur` (34). BN alternative: `ব্যাচ ১ শুরু আজ বিকেল ৫টায়`
- Description: `First class free | WhatsApp now`
- CTA: **Send WhatsApp Message**. Pre-filled message: `I want to join RHCSA Batch 1 today (C3A)`
- Creative: the 8A image (a bold "TODAY 5 PM", the address with a map pin, the phone number in large type). **For the pre-built ad, use a version without a seat number.**

*Ad C3-B, today or Batch 2 (8B creative, no clock time)*
- EN:
  > RHCSA Batch 1 starts at 5:00 PM today in Mirpur, and the first class is free. WhatsApp 01835350647 to confirm your seat.
  >
  > Can't make it today? Batch 2 starts Sun 1 Nov, 7:15 to 9:00 PM (then Fri & Sat), at the same 9,900 BDT launch fee (45% off, Batches 1 & 2 only). 15 seats. Exam voucher not included.
  > Enroll: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c3b_today_or_b2
- BN:
  > RHCSA ব্যাচ ১ শুরু আজ বিকেল ৫:০০টায়, মিরপুরে, প্রথম ক্লাস ফ্রি। সিট কনফার্ম করতে WhatsApp করুন 01835350647।
  >
  > আজ আসতে পারছেন না? ব্যাচ ২ শুরু রবিবার ১ নভেম্বর, সন্ধ্যা ৭:১৫–রাত ৯:০০ (এরপর প্রতি শুক্র ও শনি), একই ৯,৯০০ টাকা লঞ্চ ফি (৪৫% ছাড়, শুধু ব্যাচ ১ ও ২)। ১৫টি সিট। Exam voucher অন্তর্ভুক্ত নয়।
  > ভর্তি: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c3b_today_or_b2
- Headline: `Today 5 PM, or Batch 2 on 1 Nov` (31). Description: `Same 9,900 BDT launch fee`
- CTA: **Send WhatsApp Message**. Pre-filled message: `Hi, RHCSA Batch 1 or Batch 2? (C3B)`
- Creative: an 8B variant **without "2.5 HOURS TO GO"** (a pre-built ad can't show a time-specific countdown truthfully all day). Use "TODAY 5 PM" with the lower third "Can't make it? Batch 2: Sun 1 Nov, 7:15 PM. 15 seats, same 9,900 BDT". Only show "[X] seats left" if you build it on the day with the true count.

**What C tests:** C1 to C3 each test **evergreen risk removal vs the real seat count**. C3 also tests **"today only" vs "today or Batch 2"**. The C3 result matters most for the Batch 2 push: if C3-B gets the cheaper conversations, lead the Batch 2 retargeting with the Batch 2 date.
**Decision rule:** each C ad set lasts less than a day, so **don't pause on performance within a day** (the data is too thin). Pause only for (a) a wrong or stale seat count, (b) a rejected ad, or (c) Batch 1 filling. Compare across C1 to C3 at the wrap-up on 16 Oct.

**C4: Batch 2 bridge (Thu 15 Oct, 5:00 PM to 11:59 PM)**

*Ad C4-A, Batch 2 is open (use this if Batch 1 still has seats or its status is unclear)*
- EN:
  > RHCSA Batch 1 has started. Batch 2 is open: first class (free demo) Sun 1 Nov, 7:15 to 9:00 PM, then every Fri & Sat, 7:15 to 9:00 PM, in person in Mirpur.
  >
  > Same instructor (Senior SRE Md Nazmul Alam), same 25-class syllabus, the same 9,900 BDT launch fee (regular 18,000 BDT, 45% off, Batches 1 & 2 only). 15 seats. Full refund within 3 days of the first class. Exam voucher not included.
  > Reserve your Batch 2 seat: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b2&utm_content=c4a_b2_bridge
- BN:
  > RHCSA ব্যাচ ১ শুরু হয়েছে। ব্যাচ ২-এ ভর্তি চলছে: প্রথম ক্লাস (ফ্রি ডেমো) রবিবার ১ নভেম্বর, সন্ধ্যা ৭:১৫–রাত ৯:০০, এরপর প্রতি শুক্র ও শনি সন্ধ্যা ৭:১৫–রাত ৯:০০, মিরপুরে সরাসরি ক্লাস।
  >
  > একই ইন্সট্রাক্টর (Senior SRE মো. নাজমুল আলম), একই ২৫ ক্লাসের সিলেবাস, একই ৯,৯০০ টাকা লঞ্চ ফি (নিয়মিত ১৮,০০০ টাকা, ৪৫% ছাড়, শুধু ব্যাচ ১ ও ২)। ১৫টি সিট। প্রথম ক্লাসের ৩ দিনের মধ্যে সম্পূর্ণ রিফান্ড। Exam voucher অন্তর্ভুক্ত নয়।
  > ব্যাচ ২-এর সিট রিজার্ভ করুন: https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b2&utm_content=c4a_b2_bridge
- Headline: `RHCSA Batch 2: starts Sun 1 Nov` (31). BN alternative: `ব্যাচ ২ শুরু ১ নভেম্বর, সন্ধ্যা ৭:১৫`
- Description: `Last launch-fee batch | 15 seats`. This is true: the 45% discount applies to Batches 1 & 2 only.
- CTA: **Send WhatsApp Message**. Pre-filled message: `I'd like to reserve a seat in RHCSA Batch 2 (C4A)`
- Creative: **a new image is needed** (it isn't in the plan). Brief: same brand template as 1A. Headline "BATCH 2 IS OPEN". "First class Sun 1 Nov, 7:15 PM (FREE demo) | then Fri & Sat, 7:15 to 9 PM | ~~18,000~~ 9,900 BDT, 45% off (Batches 1 & 2 only) | 15 seats | In person, Mirpur". Footer with the URL and 01835350647. No Red Hat logo. Sizes 1080x1350 and 1080x1920.

*Ad C4-B, only if Batch 1 is actually full (it replaces C4-A; they never run together):* use the plan's 6B "Batch 1 is full" variant. EN: "Batch 1 is FULL. Thank you! Batch 2 is now open: first class Sun 1 Nov, 7:15 to 9:00 PM, then Fri & Sat. Same 9,900 BDT launch fee, 15 seats. Exam voucher not included." BN: "ব্যাচ ১-এর সব সিট পূর্ণ, ধন্যবাদ! ব্যাচ ২-এ ভর্তি চলছে: প্রথম ক্লাস রবিবার ১ নভেম্বর, সন্ধ্যা ৭:১৫–রাত ৯:০০, এরপর শুক্র ও শনি। একই ৯,৯০০ টাকা লঞ্চ ফি, ১৫টি সিট। Exam voucher অন্তর্ভুক্ত নয়।" Same headline and CTA as C4-A. `utm_content=c4b_b1_full`. Pre-filled message `(C4B)`.
C4 is a short bridge into the separate 15 USD Batch 2 push. It doesn't need an A/B test of its own.

---

## 4. Day-by-day launch and monitoring checklist (8 to 15 Oct)

Daily routine (every day the ads run), at **10:00 AM and 8:00 PM**:
- Check spend pacing.
- Check delivery status. "Learning limited" is expected at this budget and is not a problem.
- Check for rejected ads.
- Check frequency.
- Check comments on the ads. Hide spam, and send questions to community-responder using the plan's section 6 replies.
- Answer WhatsApp **within 15 minutes between 9 AM and 9 PM**. Log the ad code from each pre-filled message.

| Date | Tasks |
|---|---|
| **Thu 8 Oct** | 1) Confirm the ad account time zone is Asia/Dhaka, a payment method is added, and the WhatsApp number is connected to the Page (setup checklist, section 8). 2) After 1A is posted at 1 PM: build **ad set A** with **A1 (existing post 1A)** and **A2 (Bangla-first, new)**, and publish. Target live by about 4 PM. 3) Set the WhatsApp Business greeting, away message and quick replies. 4) 8 PM check: is it delivering? Was anything rejected? |
| **Fri 9 Oct** | 1) Morning check of A. 2) **Confirm the demo-class registration process** (it's required for A3). 3) After 2B is posted at 9 PM, add **A3 (existing post 2B, with the voucher line added)** to ad set A, about 9:30 PM. 4) Make sure the **5A reel and 5B image files** are final (they are needed for ad set B). |
| **Sat 10 Oct** | 1) **9 PM: A decision rule** (A1 vs A2). Record the winning language order. 2) **Build ad set B** (B1, B2) scheduled for 12 Oct, 12:00 AM, and submit it by 9 PM. 3) Create the custom audiences in section 2.2 so they start filling. |
| **Sun 11 Oct** | 1) Check **retargeting audience size** and apply the size fallback if needed (2.2). 2) **Build C1, C2, C3 and C4-A** with schedules and submit them. Also build the C4 Batch 2 image. 3) Seat update #1 (organic 4B) goes out with the true count. Log the count for the [X] ads. 4) A ends at 11:59 PM. Note A's final cost per conversation. |
| **Mon 12 Oct** | 1) B starts at 12:00 AM. Morning check: delivering and approved? 2) **By 2 PM: decision on the optional 20 to 30 USD top-up** (criteria in section 6). If approved, raise the lifetime budgets as described there. 3) Update the enrolled-students customer list (with consent). |
| **Tue 13 Oct** | 1) C1 starts at 12:00 AM. **Before 9 AM, build C1-B with the TRUE seat count** (or skip it if the count isn't urgent). 2) **2 PM: B decision rule.** 3) B ends at 11:59 PM. 4) If the Batch 1 seats reach 0, follow the "Batch 1 fills early" steps below. |
| **Wed 14 Oct** | 1) C2 starts at 12:00 AM. **Before 9 AM, build C2-B with the TRUE count.** 2) Watch frequency: if C2 goes above about 5 in the day, pause C2-B and let C2-A run alone. 3) If the optional FB Live (8 PM) is approved, the organic team runs it; no ad changes are needed. 4) Update the customer list. |
| **Thu 15 Oct** | 1) C3 starts at 12:00 AM. **Before 9 AM, check the seat count** and build or update any [X] variant. 2) Monitor WhatsApp closely all day. C3 is set up for "call or WhatsApp now". 3) **4:30 PM: C3 ends automatically.** 4) **5:00 PM: C4 starts automatically (Batch 2 messaging).** Check that all Batch 1 ads are off and C4 is delivering. 5) After 5 PM: tell the organic team to switch the bio and pinned post to Batch 2 (plan checklist). 6) Ask attendees at the demo for permitted quotes and photos for the Batch 2 ads. |
| **Fri 16 Oct** (wrap-up) | Export the results (section 5 KPIs) per ad. Match the ad codes to form submissions and enrolments. Any unspent burst budget rolls into the Batch 2 bucket. Hand the learnings to the Batch 2 push. |

**If Batch 1 fills early (at any point):**
1. Pause ad sets A, B, C1, C2 and C3 (whichever are active or scheduled) immediately.
2. Change C4's start time to now. **Use C4-B ("Batch 1 is full")** and move the unspent C1 to C3 budget into C4, up to that day's planned C amount.
3. Tell community-responder and the organic team so every reply points to Batch 2.
4. Don't run any ad that still says "[X] seats left in Batch 1".

---

## 5. KPIs and indicative benchmarks

There is no account history, so these are **rough planning ranges for small local education campaigns**, not promises. The point is to spot something clearly broken, not to grade success.

| KPI | How to read it | Indicative range | Red flag |
|---|---|---|---|
| Cost per messaging conversation started (main KPI) | Spend ÷ conversations started | About 0.15 to 1.00 USD for a niche Dhaka audience | Above about 1.50 USD after 2+ USD spent |
| Link / WhatsApp CTR | Clicks on the CTA ÷ impressions | About 0.5% to 1.5% | Below 0.4% after 1,000+ impressions |
| CTR (all) | All clicks ÷ impressions | About 1% to 3% | |
| CPC (link) | Spend ÷ link clicks | About 0.05 to 0.30 USD | |
| CPM | Cost per 1,000 impressions | About 0.50 to 2.50 USD | Above 4 USD usually means an audience that's too narrow |
| Reel hook rate | 3-second plays ÷ impressions | 20% to 30% | Below 15% |
| Reel 50% view rate | 50% views ÷ 3-second plays | 15% to 30% | |
| Frequency | Impressions ÷ reach | A/B under 2.5 for the run; C up to about 4 to 6 over 3 days | C above 7 means the audience is too small (widen it, see 2.2) |
| Conversation quality (manual) | Share of chats that ask about fee, schedule or seat, or submit the form | Track it, no benchmark yet | Mostly spam or "price?" with no follow-up |
| Form submissions / seat confirmations / demo attendance (manual) | From the ad codes and "Where did you hear about us?" | Owner targets (plan section 1) | |
| ROAS (manual) | Fee revenue from enrolments attributed to ads ÷ ad spend | Only meaningful **after 18 Oct** (when the 3-day refund window closes) | |

Rough scale for context (not a forecast): 20 USD at these CPMs is likely to buy somewhere in the region of 8,000 to 40,000 impressions, and a modest number of WhatsApp conversations, often in the tens rather than the hundreds. One enrolment (9,900 BDT, roughly 80 USD at current rates; check your card's rate) would cover the whole burst several times over. That is why WhatsApp response speed matters more than squeezing a few cents off the cost per conversation.

Meta reports **conversations**, not enrolments. Only the ad codes in pre-filled messages, the UTM-tagged form visits and the "Where did you hear about us?" question can connect ad spend to seats.

---

## 6. Optional 20 to 30 USD top-up: decision on Mon 12 Oct, by 2 PM

This money is outside the 40 USD monthly budget. **The owner decides.** Don't take it from the Batch 2 bucket.

**Top up only if ALL of these are true:**
1. **Seats:** Batch 1 still has more open seats than the owner's threshold (the plan suggests about half, so 8 or more of 15 open).
2. **The ads are working:** ad set A produced conversations at roughly 1 USD or less each, and at least a few became real enquiries (asked about schedule or seats, or submitted the form). If A produced almost nothing, extra money won't fix that. Change the creative or targeting instead.
3. **Capacity:** someone can answer WhatsApp within about 15 minutes from 9 AM to 9 PM on 12 to 15 Oct.
4. **No policy problems:** no rejected ads or account warnings.

**Don't top up if:** 3 or fewer seats are left (organic and WhatsApp follow-up can close those), or criterion 2 fails.

**Where to put it (it depends on audience size, checked on 11 Oct):**
- **Retargeting audience about 1,000 or more:** put about 70% into C (for a 25 USD top-up: C1 +5, C2 +6, C3 +6.50) and about 30% into B (+7.50, and extend B's end to Wed 14 Oct, 11:59 PM).
- **Retargeting audience under about 1,000:** put no more than about 5 to 8 USD into C, because more would push frequency well above 6. Put the rest into B (extended through Wed 14 Oct) to grow the warm pool.
- How: edit each ad set's lifetime budget. A budget or end-date edit doesn't send the ads back to creative review.

---

## 7. UTM links and tracking reference

Base: `https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=<campaign>&utm_content=<ad code>`
The owner must confirm that the site and form still work with parameters (plan checklist). If they break the form, remove the parameters and rely on the WhatsApp ad codes.

| Ad | Exact URL | WhatsApp pre-filled code |
|---|---|---|
| A1 | (existing post, plain link; tracked via WhatsApp) | A1 |
| A2 | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=a2_launch_bn | A2 |
| A3 | (existing post, plain link; tracked via WhatsApp) | A3 |
| B1 | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=b1_root_reel | B1 |
| B2 | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=b2_riskfree | B2 |
| C1-A | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c1a_still_deciding | C1A |
| C1-B | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c1b_seats | C1B |
| C2-A | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c2a_tomorrow | C2A |
| C2-B | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c2b_seats | C2B |
| C3-A | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c3a_today | C3A |
| C3-B | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content=c3b_today_or_b2 | C3B |
| C4-A | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b2&utm_content=c4a_b2_bridge | C4A |
| C4-B | https://skills.sombhabona.org/?utm_source=meta&utm_medium=paid_social&utm_campaign=rhcsa_b2&utm_content=c4b_b1_full | C4B |

**Only for the Traffic fallback** (a website destination instead of WhatsApp): put `https://skills.sombhabona.org/` in the Website URL field, and add this in the "URL parameters" field so Facebook and Instagram are split automatically:
`utm_source={{site_source_name}}&utm_medium=paid_social&utm_campaign=rhcsa_b1&utm_content={{ad.name}}&utm_term={{placement}}`

**WhatsApp click link for organic use and bios** (not for ads): `https://wa.me/8801835350647?text=Hi%2C%20I%27d%20like%20details%20about%20RHCSA%20Batch%201`

---

## 8. Owner setup checklist (before the first ad goes live on Thu 8 Oct)

**Accounts, access, payment**
- [ ] A Meta Business portfolio that owns the Facebook Page, the Instagram account and the ad account. Instagram is connected to the Page and to the ad account.
- [ ] **Page roles:** whoever builds the ads has full control of the Page and the ad account (Business settings > People). Whoever answers WhatsApp has access to the WhatsApp Business app.
- [ ] **Ad account time zone is Asia/Dhaka.** It is fixed when the account is created. If it is different, tell ads-expert so the schedules can be converted.
- [ ] **Payment method:** a card enabled for international and online transactions (a dual-currency or international card), with an available limit of at least 20 USD plus any top-up. Note that **Meta may add VAT or taxes on top of the ad spend** for Bangladeshi accounts, so check the billing summary. Set an **account spending limit** of 20 USD (or 40 to 50 USD if the top-up is approved) as a safety cap.
- [ ] Confirm that none of October's 40 USD has been spent yet, and approve the split: 20 now, 15 for Batch 2, 5 reserve (plan checklist).

**WhatsApp**
- [ ] 01835350647 runs on the **WhatsApp Business app** (or Platform) and is **connected to the Facebook Page** (Page settings > Linked accounts > WhatsApp; verify with the code).
- [ ] Greeting message (EN + BN), away message for after 9 PM ("We'll reply from 9 AM. Enroll anytime: skills.sombhabona.org"), and quick replies for fee, schedule, voucher/certificate, refund and demo, using the plan's section 6 answers.
- [ ] Labels in WhatsApp: "Ad lead", "Form submitted", "Seat confirmed", "Batch 2". Log the ad code from each pre-filled message.

**Tracking**
- [ ] **Meta Pixel** (owner to confirm): install it on skills.sombhabona.org with PageView, and **Lead** on form submit or the thank-you page. Verify the domain in Business settings. Without it, the website-visitor and form-submitter audiences are skipped; the rest of the plan still works.
- [ ] **UTM test:** open one UTM link from section 7, submit a test form, and confirm the form works. If an analytics tool is on the site, confirm the visit appears.
- [ ] An enquiry log (sheet) with columns: date, name, phone, channel, ad code, "Where did you hear about us?", status, batch.
- [ ] Customer list of enrolled students (phone numbers, **with their consent**) for exclusions, updated daily from 12 Oct.

**Creatives to upload (all without the Red Hat logo or badge images unless permission is confirmed)**
- [ ] 1A launch image, 1080x1350 plus a 1080x1920 crop. Needed: today.
- [ ] 2B free-demo reel, 9:16, with English subtitles plus a 4:5 crop. Needed: Fri 9 Oct. It needs the demo-registration process confirmed.
- [ ] 5A instructor reel, 9:16, with EN/BN captions and no exam content. Needed: **Sat 10 Oct**.
- [ ] 5B risk-free image, 1080x1350 plus 1080x1920. Needed: Sat 10 Oct.
- [ ] 6B seat-update image template, with the number left editable. Needed: Tue 13 Oct morning.
- [ ] 7B "Tomorrow 5 PM" reel or image, **without a seat number**. Needed: Sun 11 Oct.
- [ ] 8A "Today 5 PM" image, **without a seat number**, plus the 8B variant **without "2.5 hours to go"**. Needed: Sun 11 Oct.
- [ ] NEW: the C4 "Batch 2 is open" image (brief in C4), plus a "Batch 1 is full" version. Needed: Sun 11 Oct.

**Policy and content confirmations**
- [ ] Red Hat logo / badge permission: yes or no. The default is text only.
- [ ] Demo class: confirm whether non-enrolled people can attend, whether they must register, and whether attendance is capped (it affects A3 and C copy).
- [ ] Seat counts: one person owns the true count and posts it in the team chat by 8:30 AM on 13, 14 and 15 Oct.
- [ ] If Ads Manager asks about a Special Ad Category (Employment), tell ads-expert before accepting (section 1).
- [ ] Decide on the top-up on Mon 12 Oct by 2 PM (section 6).

---

### Sources consulted (policy)
- [Jon Loomer: Special Ad Categories guide](https://www.jonloomer.com/special-ad-categories-meta-ads/)
- [Data Axle: Meta Special Ad Categories rules](https://www.data-axle.com/resources/blog/meta-special-ad-categories-rules/)
- [ConductAtlas: Meta Employment ads special ad category summary](https://conductatlas.com/platform/meta/meta-special-ad-category-requirements/employment-ads-special-ad-category/)
These are third-party summaries of Meta's policy. Meta's Business Help Center and the prompt inside Ads Manager are the authoritative sources.
