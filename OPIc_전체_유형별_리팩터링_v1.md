# OPIc IH/IM3 전체 리팩터링 스크립트 v1

> 기준: 기존 75초 스크립트의 사실관계와 표현을 최대한 유지하고, 새 표현은 최소화한다.  
> 목표: IM3 안정 + IH 도전.  
> 핵심: **앞문제에서 깊은 콘텐츠를 소모하지 않고, 뒤문제에 좋은 Story Asset을 남긴다.**

---

# 0. 전체 Freeze 규칙

## 유형별 목표

| 유형 | 역할 | 목표 발화 |
|---|---|---:|
| 유형 1 | 묘사/소개 | 약 50~60초 |
| 유형 2 | 루틴/활동/과정 | 약 50~60초 |
| 유형 3 | 최근/최초/변화 경험 | 약 60~70초 |
| 유형 4 | 기억에 남는 경험 | 약 70~80초 |
| 유형 6 | 질문하기 | 약 50~60초 |
| 유형 7 | 문제 해결/대안 | 약 55~70초 |
| 유형 8 | 유사 과거 문제 경험 | 약 65~80초 |
| 유형 9 | 비교/변화 | 약 65~75초 |
| 유형 10 | 이슈/의견 | 약 70~80초 |

## 최상위 콘텐츠 규칙

1. **유형 1·2와 유형 3·4의 내용 깊이가 겹치면 깊은 내용은 3·4에 남긴다.**
2. 유형 1·2는 Core를 억지로 늘리지 않는다.
3. 유형 1·2의 시간은 **Opening + 간단한 Core + Closing**으로 확보한다.
4. 특정 날짜, 예상 밖 사건, 문제, 반전, 강한 감정은 3·4에서 우선 사용한다.
5. 유형 3과 4가 겹치면 더 강한 Story Asset은 유형 4에 남긴다.
6. 유형 9는 Past + Present를 명확하게 보여준다.
7. 유형 10은 **One issue + One reason + One example** 원칙으로 간다.
8. 롤플레이는 주제별 암기보다 **공통 뼈대 + Scenario Pack**으로 준비한다.
9. 기존에 외운 표현을 최대한 재사용한다.
10. 시험장에서 스크립트 그대로 나오지 않아도 `/` 덩어리와 흐름을 기반으로 자유롭게 이어간다.

---

# 1. 자기소개

## Q1 — 자기소개

Hi Eva, / nice to meet you. / My name is GeonTae Kim, / and I'm 25 years old.

I'm currently a senior / majoring in electronic engineering, / and I'm preparing / to start my career as an engineer.

These days, / I'm especially interested in / smart factories and automation systems. / I also worked / on a graduation project / about detecting drone signals / using SDR.

As for my personality, / my friends say / I'm funny and responsible.

In my free time, / I like working out, / traveling, / watching YouTube, / and visiting good restaurants.

In the future, / I want to become / a capable engineer / and also a warm-hearted person / for my family.

So I guess / that's everything about me. / I'm really looking forward to / starting a new chapter / in my life.

**흐름:** 25살 → 전자공학 4학년 → 스마트팩토리/자동화 → 졸업프로젝트 → 성격 → 취미 → 미래

---

# 2. 집 Topic Pack

## 유형 1-A — 현재 집 묘사

**질문**
- Tell me about the home you live in.
- Describe your house or apartment.

Well, / that's a good question.

I live alone / in a small studio apartment, / and I've been living there / for about three years.

Since it's a studio, / everything is in one open space. / I have my bed near the window, / a small desk, / a kitchen area, / and a few basic appliances.

I don't have much furniture / because the apartment is not very big, / so I keep / only the things I really need.

What I like most about my place / is that it's quiet and comfortable.

Overall, / my apartment is small and simple, / but it feels cozy, / and I'm quite satisfied / with where I live.

**흐름:** 혼자 원룸 → 3년 → 한 공간 → 기본 가구 → 최소한만 → 조용하고 편안함

---

## 유형 1-B — 좋아하는 공간

Well, / my favorite part of my home / is definitely the area around my bed.

Since I live / in a small studio apartment, / I don't really have separate rooms.

My bed is right next to the window, / and I also have / a small desk / and a thick beige rug nearby.

I like that area / because it feels very cozy and comfortable.

When I open the window, / fresh air comes in, / and the whole space feels / calm and refreshing.

Overall, / it may look like / a very simple corner, / but for me, / it's the most comfortable place / in my apartment.

**보호:** YouTube / reading / stress relief는 유형 2로 넘김.

---

## 유형 2 — 집에서 평소 하는 활동

Well, / when I'm at home, / I usually spend most of my free time / around my bed.

After a long day, / I usually lie on my bed / and watch YouTube.

Sometimes, / I sit at my desk / and read a book, / or I just do nothing / and relax.

I really enjoy / spending time alone there / because I can relax / without being disturbed.

It's a pretty simple routine, / but it helps me forget about / school, work, and stress / for a while.

Overall, / staying at home / is one of my favorite ways / to relax and recharge.

---

## 유형 3 — 집에 준 변화

I haven't made any huge changes / to my apartment / because it's a small studio, / but I've made a few changes / to make it more comfortable.

The biggest one / was replacing my old bed.

It wasn't very comfortable, / so I bought a new one, / and after that, / I started sleeping / much better.

I also bought / a thick beige rug / and put it near my bed.

Another thing I did / was move my bed and desk / a little closer to the window.

Now I can get / more sunlight and fresh air / while I'm sitting there.

None of these changes / were expensive or dramatic, / but together / they made my apartment feel / much more like my own place.

Now it's small, / but very comfortable / and relaxing.

---

## 유형 4 — 집에서 생긴 문제

One memorable problem I had at home / happened on a Saturday morning.

When I woke up, / I noticed that the bathroom floor / was covered with water.

At first, / I had no idea / where it was coming from, / so I checked the bathroom carefully / and realized / that the toilet was leaking.

I got pretty stressed / because I live alone / and I didn't know / how to fix it.

So I called a plumber right away / and explained the problem.

Unfortunately, / he couldn't come immediately, / so I had to wait / for about an hour.

When he finally arrived, / he checked the toilet / and fixed the leak / pretty quickly.

The problem itself was solved, / but I still had to clean up / all the water on the floor.

It was annoying at the time, / but it taught me / that living alone means / I sometimes have to deal with / unexpected problems / by myself.

---

## 유형 9 — 과거 집 vs 현재 집

Well, / my living situation / has changed a lot in many ways.

In the past, / I lived with my family / in a spacious apartment.

It had several bedrooms, / two bathrooms, / and a large living room. / My family often spent time together there, / so the apartment felt / bright and lively.

But about three years ago, / I moved out / and started living alone / in a small studio apartment.

Now, / my bed, desk, kitchen area, and living space / are all in one room, / so my current home / is much smaller.

However, / I have my own space now, / so I can relax / whenever I want / without being disturbed.

I sometimes miss / the larger family home, / but at this point, / I prefer my studio / because it's quiet, cozy, / and easy to manage.

---

# 3. 집에서 보내는 휴가 Topic Pack

## 유형 2 — 평소 집에서 보내는 휴가

Well, / I actually enjoy / spending some of my vacations at home, / especially when I'm physically / or mentally tired.

On a typical day off, / I wake up late / and have a simple breakfast.

After that, / I usually lie on my bed / and watch YouTube / or read webtoons.

I especially like / travel channels / such as Pani Bottle and KwakTube / because I can see different countries / without leaving my room.

I don't force myself / to exercise or be productive / because the whole point / is to rest.

Overall, / a stay-at-home vacation is cheap, / comfortable, / and one of the best ways / for me to recharge.

**삭제한 깊이:** 특정 월요일/기말고사/가족 치킨·피자는 유형 4에 보존.

---

## 유형 4 — 기억에 남는 집에서의 휴가

The most memorable stay-at-home vacation / I can remember / was the Monday / after my final exams ended.

I had just finished / a stressful semester / and gone back to my parents' home.

I had no classes, / deadlines, / or plans, / so for the first time in a long while, / I felt completely free.

I woke up late / and spent most of the day / lying around. / I watched YouTube / and caught up on webtoons / that I had saved.

I remember watching / a KwakTube honeymoon video / about Europe, / and I started imagining / traveling there / for my own honeymoon someday.

Later, / my family came home from work. / We ordered chicken and pizza, / ate together, / and talked about ordinary things.

Nothing exciting happened that day, / but that was exactly why / it felt special.

I had nothing to worry about / and could simply enjoy / resting with my family.

---

## 유형 10 — 좋은 휴가에 대한 의견

I think / a good vacation is one / that gives you what you need.

Everyday life / can be exhausting / because people spend a lot of time / working, studying, / or dealing with responsibilities.

Some people like / active vacations / because they want / new experiences and special memories.

Other people prefer / staying at home / and simply resting, / especially when they're really tired.

Personally, / I enjoy both. / If I want new experiences, / I like traveling. / But when I'm exhausted, / I prefer a quiet day at home.

Overall, / I don't think / there is one perfect type of vacation. / A good vacation should help you / return to daily life / feeling refreshed.

---

# 4. 공원 Topic Pack

## 유형 1 — 좋아하는 공원

Well, / that's a good question.

My favorite park / is North Port Waterfront Park / in Busan.

It's located / right behind Busan Station, / and it's only about / a fifteen-minute walk / from my home.

The park has / nice walking trails, / plenty of benches, / and some outdoor sports facilities.

My favorite part / is the garden area. / In spring, / a lot of flowers start to bloom, / so the whole place feels / fresh and pleasant.

Even though it's / in the middle of a big city, / it feels very peaceful.

Overall, / I really like this park / because it's close to my home / and I can easily enjoy nature there.

---

## 유형 2 — 공원에서 하는 활동

Well, / when I go to the park, / the main thing I do there / is exercise.

I usually go there / early in the morning, / and I often exercise alone.

First, / I run about three kilometers / on the running path.

If I still have some energy left, / I use the outdoor workout machines / for a little while.

After that, / I stretch my arms and legs / and cool down.

Sometimes, / when the weather is nice, / I just take a walk / with friends or family.

Overall, / my routine is pretty simple, / but I really enjoy it.

Being outdoors / feels much more refreshing / than running on a treadmill.

---

## 유형 4 — 기억에 남는 공원 경험

One of my most memorable experiences / at the park / happened last fall.

There was a small weekend festival, / so I went there alone / to relax.

There were food trucks, / small booths, / and live music, / so the atmosphere / was really lively.

While I was walking around, / I decided to pass by / a bench / that I used to sit on / with my ex-girlfriend.

But when I got close to the bench, / I suddenly saw her / sitting there / with another guy.

I really didn't expect that, / so I was completely shocked.

To make things worse, / I was wearing very casual clothes, / so I felt even more awkward.

I pretended not to see them / and quickly walked away.

At the time, / it was really uncomfortable, / but now / I think it's kind of funny.

That's why / I still remember that day / so clearly.

---

## 유형 10 — 공원/관광지 문제: 혼잡

I think / one of the biggest problems / with popular parks / is that they can get too crowded.

This is especially true / on weekends / when many people come / with friends or family.

Because of that, / the park can become noisy, / and sometimes it's hard / to relax.

Personally, / I don't really enjoy that / because I usually go to the park / to exercise / or clear my head.

So I prefer / going early in the morning / when there are fewer people.

Overall, / I still enjoy popular parks, / but I think / they are much better / when the atmosphere is peaceful.

---

# 5. 해변 Topic Pack

## 유형 1 — 좋아하는 해변

Well, / my favorite beach / is Gwangalli Beach / in Busan.

I'm originally from Busan, / so I've visited many beaches there, / but Gwangalli is the one / I like the most.

It takes about thirty minutes / to get there by bus / from my home, / so it's easy to visit.

The best part / is the night view.

When it gets dark, / Gwangandaegyo Bridge / lights up over the water, / and the whole area / looks beautiful.

I also really like / the sound of the waves / because it helps me relax.

Overall, / Gwangalli has / both a lively city atmosphere / and a relaxing beach atmosphere, / so it's definitely / my favorite beach.

**보호:** 돗자리/간식/산책은 활동·경험용으로 아낌.

---

## 유형 2 — 해변에서 하는 활동

Well, / when I go to Gwangalli Beach, / I usually go with my friends / when the weather is nice.

During the day, / we spread out a picnic mat, / eat snacks, / and talk for a while.

Sometimes, / we take a walk / along the beach / and take pictures.

I really like / listening to the waves / because it helps me relax / and clear my head.

When it gets dark, / we usually watch / the night view / of Gwangandaegyo Bridge.

Overall, / I don't do anything complicated there. / I just enjoy / spending time with my friends / and relaxing by the ocean.

---

## 유형 4 — 기억에 남는 해변 경험

One of my most memorable trips to the beach / happened last summer.

One of my close friends / was feeling really tired, / so we suddenly decided / to go to Gwangalli Beach together.

We took a bus there / in the late afternoon, / and luckily, / the weather was perfect.

We bought some beverages and snacks, / spread out a picnic mat, / and talked for a long time.

Later, / we walked near the water / and took pictures of the sunset.

As it got darker, / Gwangandaegyo Bridge lit up, / so we sat on a bench / and watched the night view / while listening to the waves.

My friend looked / much more relaxed / by the end of the day.

It wasn't an expensive / or special trip, / but it became a meaningful memory / because we could forget about / our worries together.

---

## 유형 10 — 해변 문제: 쓰레기

I think / one problem at popular beaches / is trash.

A lot of people / bring food and drinks / to the beach, / but some people leave / bottles, cans, / or food containers behind.

Because of that, / the beach can become dirty / and unpleasant.

I really don't like that / because people go to the beach / to enjoy the ocean / and relax.

So I think / everyone should clean up / after themselves / before they leave.

Overall, / beaches are great places to relax, / but keeping them clean / is really important.

---

# 6. 캠핑 Topic Pack

## 유형 2 — 캠핑 갈 때 챙기는 물건

Well, / when I go camping near the beach, / I usually go / with three close friends / and stay for one night.

We try to bring / only the things we really need.

The main items are / a tent, / sleeping bags, / camping chairs, / and a small table.

I also pack / a change of clothes, / towels, / bottled water, / sunscreen, / and a portable charger.

One thing we always bring / is a Bluetooth speaker / because we enjoy listening to music / while relaxing together.

Overall, / it still sounds like a lot, / but we divide everything / among four people, / so it's easy enough to carry.

---

## 유형 3 — 최근 캠핑 경험

The last time I went camping / was earlier this summer.

I went on a two-day, one-night trip / with three of my close friends / to a campsite / near Songjeong Beach in Busan.

We had all been busy and tired, / so we wanted / a relaxing weekend.

When we arrived, / we set up our tent, / chairs, / and table.

Setting up the tent / was harder than we expected, / so all four of us / had to work together.

After that, / we walked along the beach, / took pictures, / and listened to the waves.

In the evening, / we ate dinner together / while watching the sunset.

Later, / we sat outside the tent, / listened to music, / and talked for hours.

It was only a short trip, / but I really enjoyed / spending time with my friends.

I'd definitely like / to go again.

---

## 유형 4 — 같은 캠핑 경험이 memorable로 나오면

> 이 주제는 **새로운 사건을 억지로 만들지 않는다.**  
> 현재 송정 캠핑 이야기를 그대로 사용하되 마지막 감정 부분을 조금 더 살린다.

The last time I went camping / was earlier this summer, / and it became / one of my most memorable camping trips.

I went / with three of my close friends / to a campsite / near Songjeong Beach.

We had all been busy and tired, / so we wanted / a relaxing weekend.

Setting up the tent / was harder than we expected, / but all four of us / worked together / and finally finished it.

After that, / we walked along the beach / and watched the sunset.

Later, / we sat outside the tent, / listened to music, / and talked for hours.

What I remember most / is falling asleep / to the sound of the waves.

Nothing dramatic happened, / but I felt completely relaxed / because I was with close friends / and didn't have to think about / school or work.

That's why / I still remember that trip / so clearly.

---

# 7. 음악 Topic Pack

## 유형 1 — 좋아하는 아티스트

Well, / I've been into Korean hip-hop / since I was young, / and my favorite artist / is definitely Beenzino.

He's a Korean rapper, / and I've listened to his music / for years.

What I like most about him / is his unique voice / and polished rap style.

My favorite album / is 24:26 / because the lyrics are about / youth and everyday life, / so I can relate to them.

The song that first got me interested in him / was Aqua Man.

Overall, / I really like his music / because it gives me energy / and always puts me / in a good mood.

**보호:** 대학 축제/Aqua Man 라이브는 유형 4에 남김.

---

## 유형 2 — 음악 감상 습관

Well, / music is a big part / of my daily routine, / and the kind of music I choose / depends on what I'm doing.

When I work out, / I usually listen to / energetic Korean hip-hop / because the strong beats / give me energy.

On the other hand, / when I study or read, / I prefer classical music / without lyrics / because it helps me concentrate.

I usually listen / on my smartphone / with my AirPods.

I mostly use Melon, / and sometimes / I use long YouTube playlists.

Overall, / I use different kinds of music / to control my mood / and concentration.

---

## 유형 9 — 음악 취향 변화

Well, / my taste in music / has changed a lot in many ways / over the years.

When I was younger, / I mostly listened to / Korean hip-hop.

I liked rappers / such as Dynamic Duo, / E-Sens, / and Beenzino / because I enjoyed / strong beats and interesting lyrics.

But after I entered university, / things started to change.

When I studied / while listening to rap, / I sometimes paid too much attention / to the lyrics / and lost focus.

So I tried / classical music / because it had no lyrics, / and I could concentrate / much better.

These days, / I still listen to hip-hop / when I work out, / but I prefer classical music / when I study or read.

Overall, / I haven't stopped liking hip-hop. / My taste has simply / become broader.

---

## 유형 4 — 기억에 남는 음악 경험

One of my most memorable music experiences / happened at my university festival / last fall.

Beenzino, / my favorite Korean rapper, / came to perform.

I've listened to his music / for years, / so when I heard / he was coming, / I was really excited.

A few of my close friends / liked him too, / so we went to the outdoor stage / together.

We arrived early / to get a good spot, / but there were already / a lot of students.

The best moment / was when he performed Aqua Man.

That's the song / that first got me into his music, / so hearing it live / felt completely different / from listening through my AirPods.

My friends and I / sang along / and had a great time.

Even now, / whenever I hear Aqua Man, / I remember that festival.

---

## 유형 10 — 음악/공연 문제: 너무 붐빔

I think / one problem with popular concerts / is that there are / too many people.

When a concert is really crowded, / it can be hard / to get a good spot / or focus on the performance.

Sometimes, / people also talk loudly / or use their phones / during the show.

Personally, / I find that distracting / because I want to focus / on the music.

So I prefer / smaller concerts / or arriving early / when I really want / to enjoy a performance.

Overall, / concerts can be exciting, / but the crowd can sometimes / make the experience less comfortable.

---

# 8. 해외여행 Topic Pack

## 유형 1 — 좋아하는 해외 여행지: 몽골

Well, / I've traveled to several countries, / but if I had to choose my favorite, / it would definitely be Mongolia.

I went there / last summer / with two of my college friends.

The biggest reason I loved it / was the scenery.

We saw / endless grasslands, / wide-open plains, / highlands, / and parts of the Gobi Desert.

The night sky / was also amazing / because there were almost no city lights.

Mongolia felt / completely different / from city life.

Overall, / I would definitely recommend it / to anyone / who loves nature.

**보호:** 사막 꽃/게르/별/큰 개는 경험형으로 남김.

---

## 유형 2 — 여행 전 준비

Well, / I enjoy traveling abroad, / but I'm not the type of person / who plans every single detail.

I usually travel with friends, / and we discuss / the main plan together.

Before a trip, / I watch a few YouTube videos / about the destination.

The one thing / I research carefully / is food / because I love eating.

I look up / local dishes / and a few restaurants / I really want to try.

When I pack, / I try to keep it simple. / I mainly bring / my passport, / charger, / portable battery, / medicine, / some cash, / and basic clothes.

Overall, / I prefer keeping / the schedule flexible / because I don't like rushing / from one place to another.

---

## 유형 4 — 가장 기억에 남는 여행 경험

One of my most memorable travel experiences / happened in Mongolia / last summer.

I was traveling / with two college friends, / and one night / we stayed / in a traditional Mongolian ger.

After dinner, / we went outside / because we wanted / to see the stars.

There were almost no lights / around the camp, / so the sky was incredibly clear.

We sat on the ground, / looked at the stars, / had some snacks and a local drink, / and talked about / all kinds of random things.

There were also / several large dogs / near the camp.

They looked intimidating at first, / but they were actually friendly / and stayed close to us.

Nothing about that night / was expensive / or carefully planned, / but that's exactly why / I remember it.

I wasn't thinking / about school or work at all. / I was simply enjoying / the quiet grassland, / the stars, / and time with my close friends.

---

## 유형 10 — 해외여행 문제: 비용

I think / one of the biggest problems / with traveling these days / is the cost.

Flights, hotels, / and even food / can be expensive, / especially during busy seasons.

Because of that, / people may not be able / to travel as often / as they want.

Personally, / I like traveling abroad, / but I still have to think carefully / about my budget.

So I usually keep / my schedule flexible / and focus on / only a few main places / or activities.

Overall, / traveling is a great experience, / but I think / the cost is one of the biggest things / people have to consider.

---

# 9. 기술 Topic Pack

## 유형 1 — 한국에서 인기 있는 기술: 스마트폰

Well, / one of the most popular technologies / in Korea / is definitely the smartphone.

Almost everyone carries one, / and people use it / for much more than / calls and messages.

We watch YouTube, / search for information, / take pictures, / use maps, / and make mobile payments / on our phones.

I personally use / my smartphone every day / to talk with friends, / listen to music, / watch travel videos, / and look up information.

It's especially useful / when I travel abroad / because I can use maps, / translation, / and transportation information.

Overall, / smartphones are incredibly useful / because one small device / can handle so many parts / of daily life.

**보호:** 너무 오래 사용/의존 문제는 유형 10으로 이동.

---

## 유형 9 — 과거와 현재 기술 비교

Well, / technology has changed a lot / in many ways / since I was a child.

When I was younger, / my family mainly used / one desktop computer at home.

It was large, / slow, / and fixed in one place. / If someone else was using it, / I had to wait / for my turn.

These days, / things are completely different.

I have a smartphone / and a laptop, / so I can study, / communicate, / watch videos, / and search for information / almost anywhere.

For me, / the biggest change / is mobility.

Technology is no longer something / I use only at a desk. / It's with me / almost all the time.

Overall, / I prefer modern technology / because it saves time / and makes daily life / much more convenient.

**보호:** dependence/too much screen time는 유형 10으로 남김.

---

## 유형 10 — 기술 문제: 과도한 사용

I think / one of the biggest problems / with smartphones / is that people spend / too much time on them.

Smartphones are so convenient / and entertaining / that it's easy / to keep using them / longer than planned.

For example, / people watch YouTube, / use social media, / or play games / almost anywhere.

I sometimes watch YouTube / longer than I planned too, / and then I feel tired / the next day.

So I think / people need to control / how much time / they spend on their phones.

Overall, / smartphones are incredibly useful, / but I think / it's important / to use them in a balanced way.

---

# 10. 재활용 Topic Pack

## 유형 1 — 한국의 재활용 제도

Well, / recycling is a normal part / of daily life in Korea, / and the system / is fairly well organized.

Most apartment buildings have / a separate recycling area.

People sort waste / into categories / such as paper, / plastic, / cans, / glass bottles, / and vinyl.

Regular trash / and food waste / are handled separately.

Depending on the building, / people may take recycling out / on certain days / or use the recycling area / every day.

Overall, / most Koreans are used to recycling, / and I think it's important / because it reduces waste / and allows useful materials / to be used again.

**보호:** 씻기/라벨 제거/박스 접기는 유형 2로 넘김.

---

## 유형 2 — 집에서 재활용하는 과정

Well, / at home, / I try to separate recyclable items / before they pile up too much.

I keep paper and cardboard / in one area, / and I use another bag / for plastic bottles, / cans, / and glass containers.

Before I put containers / into the recycling bag, / I empty anything left inside / and rinse them with water.

I also remove labels / from plastic bottles.

For cardboard boxes, / I take off the tape, / flatten them, / and stack them together.

When the bags get full, / I take everything / to the recycling area / near my building.

Overall, / it's a simple routine, / and now / it's just part / of my normal household chores.

**보호:** 봉투 찢어짐 사건은 유형 4에 남김.

---

## 유형 4 — 기억에 남는 재활용 경험

One memorable recycling experience / happened because / I had let too many boxes / and recyclable items / pile up at home.

I had received several deliveries, / so there were cardboard boxes, / plastic bottles, / and cans / everywhere.

One evening, / I finally tried / to take everything downstairs / at once.

I carried flattened boxes / in one hand / and a large recycling bag / in the other.

Unfortunately, / the bag was too heavy / and suddenly tore.

Bottles and cans / fell out / and rolled across the floor.

I felt really embarrassed / because another resident / was passing by.

Luckily, / that person helped me / pick everything up.

I put the items / into a new bag / and made several trips / instead of carrying everything / at once.

Since then, / I try to take recycling out / regularly.

I learned / that putting off a small chore / can easily create / a much bigger job / later.

---

## 유형 10 — 재활용 문제: 귀찮아서 미루는 문제

I think / one problem with recycling / is that it takes / extra time and effort.

People have to / sort different materials, / rinse containers, / remove labels, / and flatten boxes.

When people are tired, / they may put it off / or not do it properly.

I understand that / because I also find / washing containers and removing labels / a little annoying.

Still, / I think recycling is important / because it reduces waste.

So I try / not to let recyclable items / pile up too much.

Overall, / recycling can be inconvenient, / but I think / it's worth the effort.

---

# 11. 호텔 Topic Pack

## 유형 1 — 한국 호텔 특징

Well, / there are many different kinds of hotels / in Korea, / so travelers can choose / based on their budget / and the purpose of their trip.

In large cities / like Seoul and Busan, / there are many business hotels / near subway stations / and shopping areas.

The rooms are usually not very large, / but they're clean / and have basic things / such as a comfortable bed, / a private bathroom, / and Wi-Fi.

There are also / luxury hotels / with swimming pools, / fitness centers, / and restaurants.

What I like most / about hotels in Korea / is convenience.

Overall, / Korean hotels are generally clean, / safe, / and easy to use.

---

## 유형 3 — 최근 호텔 숙박: 후쿠오카

One of my recent hotel stays / was during a trip to Fukuoka / with three of my high school friends.

We booked a hotel / in a convenient area / near public transportation / and many restaurants.

The room wasn't very large, / but it was clean / and comfortable enough / for us.

After checking in, / we dropped off our bags / and went straight outside.

We walked around the city, / visited shops, / and tried several local dishes.

After dinner, / we went back to the hotel / and stayed up late / talking about our high school days / and our current lives.

The room felt / a little crowded / with four people, / but that actually made it / more fun.

Overall, / the hotel wasn't luxurious, / but I really enjoyed / spending time with old friends.

---

## 유형 4 — 기억에 남는 호텔 경험: 홍콩

One of my most memorable hotel experiences / happened during a trip to Hong Kong / with a close friend.

Our trip was short, / so we chose a hotel / in a convenient area / near public transportation / and major tourist spots.

When we entered the room, / I was surprised / by how small it was.

Hong Kong was more expensive / than Korea, / so the room was smaller / than I expected / for the price.

Still, / it was clean, / the bed was comfortable, / and the location was excellent.

We could easily get / to Tsim Sha Tsui / and Victoria Harbour.

At night, / we went to Victoria Harbour / and looked at the bright skyline.

After walking for hours, / we went back to the hotel, / bought some snacks, / and talked about / what we had seen.

The hotel wasn't luxurious, / but its location / made the short trip easy / and became part of my memory / of Hong Kong.

---

# 12. 롤플레이 공통 뼈대

# 유형 6 — Ask

**공통 Opening**

Hello, / I'm calling because ~. / I have a few questions.

**질문 연결**

- First, / ...
- Also, / ...
- One more thing. / ...
- Finally, / ...

**공통 Closing**

Okay, / that's good to know. / Thank you for the information.

---

# 유형 7 — Solve

**공통 Opening**

Hello, / I'm calling because / there's a problem with ~.

**문제**

I ~, / but unfortunately ~.

**대안 1**

Could you please ~?

**대안 2**

If that's not possible, / I'd like ~ instead.

**Closing**

Could you please check / and let me know / what you can do?

---

# 유형 8 — Similar Past Problem

I remember one time / when I had a similar problem.

Unfortunately, / ...

I got pretty stressed / because ...

So we decided to / ...

In the end, / ...

At first, / I was disappointed, / but ...

---

# 13. Roleplay Scenario Pack A — 호텔/예약

## 유형 6 — 호텔 예약 질문

Hello, / is this the Grand Hotel?

I'm planning a trip / and I'd like to book a room. / I have a few questions / before I make the reservation.

First, / do you have any rooms available / for this weekend?

I'm traveling with a friend, / so what kind of room / would you recommend / for two people? / And how much is it / per night?

One more thing. / Do I need to pay / when I make the reservation, / or can I pay / when I check in?

Finally, / could you tell me / about your cancellation policy?

I understand. / Thank you / for all the information. / I'll talk to my friend / and call you back.

---

## 유형 7 — 예약 날짜/객실 문제

Hello, / I'm calling because / there's a problem / with my reservation.

I booked a room / for this Saturday, / but unfortunately / I need to change the date.

Could you please / move my reservation / to Sunday?

If Sunday is full, / is there another room / available / around the same price?

If that's not possible, / I'd like to cancel / the reservation instead.

Could you please check / and let me know / what you can do?

Thank you / for your help.

---

## 유형 8 — 과거 일정 취소 경험: 거제도

I remember one time / when I had a similar problem / with a trip.

My friends and I / were planning / to go to Geoje Island.

Unfortunately, / the weather was terrible / that day, / so we couldn't follow / our original plan.

We talked about / changing the schedule, / but the weather was bad / everywhere.

I was disappointed / because we had been / looking forward to the trip.

So in the end, / we decided / to cancel everything / and meet another time.

At first, / I felt really disappointed, / but I think / it was the right decision / because traveling in bad weather / wouldn't have been enjoyable.

---

# 14. Roleplay Scenario Pack B — 친구 모임/약속

## 유형 6 — 주말 모임 질문

Hi, Minsoo. / It's GeonTae.

I'm calling because / I have a few questions / about the get-together / this weekend.

First, / where is it going to be? / Is it at your place?

Also, / do I need / to bring anything?

One more thing. / What time / does it start?

By the way, / who else / is coming?

Okay, / thanks for letting me know.

I'll see you / on Saturday. / I'm really looking forward to it.

---

## 유형 7 — 약속에 못 가는 상황

Hi, Minsoo. / I'm calling because / there's a problem / with our plan.

Unfortunately, / I don't think / I can make it / at the original time.

Could we meet / a little later / instead?

If that doesn't work, / how about meeting / tomorrow?

If tomorrow is difficult too, / we could choose / another day / this week.

I'm really sorry / about changing the plan.

Let me know / what works best / for you.

---

## 유형 8

**거제도 일정 취소 경험 재사용 가능.**  
새로운 스토리를 따로 외우지 않는다.

---

# 15. Roleplay Scenario Pack C — 쇼핑/배송

## 유형 6 — 가구 질문

Hi, / I just moved / into a small studio apartment, / so I need to buy / a few pieces of furniture.

Could I ask you / a few questions?

First, / what kinds of single beds / do you have? / And how much / is that one?

Also, / do you have / a small two-seat sofa / that would fit / in a studio?

One more thing. / Do you offer / delivery and assembly services?

Finally, / is there any discount / if I buy / several items together?

Okay, / that's good to know. / Thank you / for answering my questions.

---

## 유형 7 — 가구 오배송

Hello, / I'm calling because / there's a problem / with my order.

I ordered / a black bed / and a gray sofa, / but I received / the wrong items.

Could you please / pick them up / and send me / the correct items?

If the correct bed / isn't available, / I'd like / a full refund instead.

As for the sofa, / I could keep it / if you can give me / a reasonable discount.

Could you please check my order / and let me know / what you can do?

Thank you / for your help.

---

## 유형 8 — 과거 오배송 경험

I remember one time / when I had a similar problem / with an online order.

I ordered / something in one color, / but unfortunately / I received / the wrong one.

At first, / I was pretty annoyed / because I had waited / several days / for the delivery.

So I called / customer service / and explained the problem.

They told me / they could pick it up / and send me / the correct item.

In the end, / I received / the right product / a few days later.

It was annoying at the time, / but luckily / the problem was solved / without too much trouble.

---

# 16. Roleplay Scenario Pack D — 영화표/티켓/교통

## 유형 6 — 티켓 문의 공통형

Hello, / I'd like to ask / a few questions / about the tickets.

First, / what times / are available?

Also, / how much / is one ticket?

One more thing. / Can I change / the date or time / after I buy it?

Finally, / can I get a refund / if my plans change?

Okay, / that's good to know. / Thank you / for the information.

---

## 유형 7 — 영화표 날짜 실수

Excuse me. / I have a problem / with my movie tickets.

I accidentally bought / two tickets / for tonight, / but I actually need them / for tomorrow.

Would it be possible / to change the tickets / to tomorrow's show?

Any evening time / would be fine for me.

If I can't change them directly, / could I choose / a different showtime?

If that still isn't possible, / could you tell me / what other options I have?

I'm sorry / about the mistake.

Could you please check the tickets / and tell me / what I can do?

---

## 유형 8

**날짜를 잘못 예약한 경험은 Pack A 또는 D에 공통 재사용.**  
새로운 긴 스토리는 만들지 않는다.

---

# 17. Roleplay Scenario Pack E — 식당/서비스

## 유형 6 — 식당 예약 질문

Hello, / I'd like to make / a reservation.

I have a few questions / before I book a table.

First, / do you have / a table for four / this Saturday evening?

Also, / what time / do you usually get busy?

One more thing. / Is there anything / you would recommend / on the menu?

Finally, / do I need / to make a deposit / for the reservation?

Okay, / thank you / for the information.

---

## 유형 7 — 식당 만석

Hello, / I'd like to make a reservation / for this Saturday evening.

There will be four people, / and we were hoping / to come at seven.

Oh, / you're fully booked / at seven?

Would it be possible / to come / a little earlier or later?

If those times / are also full, / could you put my name / on the waiting list?

If Saturday / is completely impossible, / do you have / a similar time / available on Sunday evening?

Thank you / for checking / all the options.

I really appreciate / your help.

---

## 유형 8 — 과거 예약 문제

**거제도 일정 취소 경험 / 호텔 예약 변경 경험 중 하나를 재사용.**  
핵심은 `problem → disappointed → discussed options → changed/canceled → right decision`.

---

# 18. 유형 10 공통 Issue Pack

유형 10은 주제마다 새 논리를 만들지 않는다.

## Pack 1 — Too Much / Dependency

적용:
- 스마트폰
- 인터넷
- SNS
- YouTube

I think / one of the biggest problems / is that people spend / too much time on ~.

The main reason / is that ~ / is very convenient / and entertaining.

For example, / people ~.

Because of that, / they sometimes ~.

So I think / people need to control / how much time / they spend on it.

Overall, / ~ is very useful, / but it's important / to use it / in a balanced way.

---

## Pack 2 — Crowded / Noise

적용:
- 공원
- 해변
- 관광지
- 공연
- 쇼핑몰

I think / one of the biggest problems / is that the place / gets too crowded, / especially on weekends.

There are too many people, / so it can become / noisy and uncomfortable.

Personally, / I don't really enjoy that / because I usually go there / to relax.

So I prefer / going early / when there are fewer people.

Overall, / I still like the place, / but the atmosphere / is much better / when it's peaceful.

---

## Pack 3 — Cost

적용:
- 여행
- 호텔
- 외식
- 영화/공연

I think / one of the biggest problems / these days / is the cost.

~ has become / more expensive, / so people can't enjoy it / as often as before.

Personally, / I also have to think / about my budget.

So I usually / keep things simple / and focus on / what I really want to do.

Overall, / I really enjoy ~, / but the cost / is something / people have to consider.

---

## Pack 4 — Environment / Cleanliness

적용:
- 해변
- 공원
- 캠핑
- 재활용
- 관광지

I think / one problem / is trash.

Some people / leave bottles, cans, / or food containers behind.

Because of that, / the place becomes / dirty and unpleasant.

I really don't like that / because everyone should be able / to enjoy a clean place.

So I think / people should clean up / after themselves.

Overall, / keeping the place clean / is really important.

---

# 19. 공통 Strategic Anchor Bank

## Opening

- Well, / that's a good question.
- Well, / let me think.
- Actually, / ...
- When it comes to ~, / ...

## 두괄식

- My favorite ~ / is definitely ...
- The main thing I do / is ...
- One of my most memorable experiences / happened ...
- I think / one of the biggest problems / is ...

## 이유/감정

- The main reason is that / ...
- I really like it / because ...
- It helps me / relax and recharge.
- I got pretty stressed / because ...
- I really didn't expect that.
- I was completely shocked.
- I felt really disappointed.
- It felt special / because ...

## 과거/현재

- Things have changed a lot / in many ways.
- In the past, / ...
- When I was younger, / ...
- But now, / ...
- These days, / ...
- In contrast, / ...
- Unlike ~, / ...

## 과정/해결

- At first, / ...
- Unfortunately, / ...
- So I decided to / ...
- So we decided to / ...
- In the end, / ...
- If that's not possible, / ...
- Could you please / ...?

## Closing

- Overall, / ...
- That's why / ...
- At the time, / it was ~, / but now ...
- That's why / I still remember that day / so clearly.
- I'd definitely like / to go again.

---

# 20. 암기 우선순위

## 가장 먼저 완벽하게

1. 유형 4 Story Asset
   - 집 변기 누수
   - 공원 전 여자친구
   - 몽골 게르/별
   - 빈지노 축제
   - 재활용 봉투
2. 유형 9
   - 집 과거/현재
   - 음악 취향 변화
   - 기술 과거/현재
3. 유형 7
   - 오배송
   - 영화표
   - 식당 만석
4. 유형 6 공통 질문 뼈대

## 그다음

- 유형 1·2는 핵심 3~4덩어리만 확실히.
- Opening/Closing은 시험장에서 자연스럽게 추가.
- 유형 10은 Issue Pack 4개를 돌려쓴다.

---

# 21. 실전 사용 규칙

질문을 들은 뒤:

**① 유형 판단**
→ 묘사 / 루틴 / 경험 / 문제 / 비교 / 이슈 / 롤플레이

**② 첫 문장으로 답부터**
→ 시험관이 바로 방향을 알 수 있게

**③ 깊이 제한**
→ 유형 1·2에서 경험 Story Asset을 꺼내지 않음

**④ 감정적 이유**
→ 행동 뒤에 왜 좋은지/왜 싫은지/왜 당황했는지

**⑤ Closing**
→ 시간이 조금 짧으면 새 사건 대신 앞 내용을 요약

예:
`Overall, / my routine is pretty simple, / but I really enjoy it / because it helps me relax.`

---

# 22. 현재 버전의 핵심

이 문서는 완전히 새로운 영어를 외우기 위한 문서가 아니다.

기존에 외운 표현을

**묘사 → 활동 → 경험 → 특별한 경험 → 비교 → 이슈 → 롤플레이**

에 맞게 재배치해서,

- 앞문제 콘텐츠 소모 감소
- 뒷문제 Story 강화
- 암기량 감소
- 시제와 감정 표현 확보
- 시험장에서 자유 발화할 재료 확보

를 목표로 한다.
