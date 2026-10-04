# indonesia proxy: how to pick residential IPs for Shopee, Tokopedia and TikTok Shop work without overpaying

Search for "indonesia proxy" and you get two very different subjects: geopolitical commentary about Indonesia as a proxy in great-power rivalry, and people who just want an IP address that looks like it belongs to someone in Jakarta. This article is about the second one.

The reason people want an Indonesian exit IP is usually mundane and specific. Shopee Indonesia shows local shipping subsidies and flash-sale stock to local addresses. Tokopedia sellers price the same SKU very differently across stores. Google's `.co.id` results differ from what you see from abroad. Ad creatives render differently. If your traffic comes out of a data center in Frankfurt, none of that shows up correctly, and on the harder endpoints your requests get rate-limited before you learn anything.

Here's what changes once your traffic genuinely exits from Indonesia: prices appear in IDR, marketplace vouchers and flash-sale availability become visible, local news and streaming pages stop blocking you, and platform risk systems see an ordinary household connection instead of a hosting range.

## Which kind of Indonesian IP you actually need

Not all local IPs behave the same, and picking the wrong type is the most common way people waste money on this.

| Your actual job | Right proxy type | Why |
| --- | --- | --- |
| Shopee / Tokopedia price and stock sweeps on desktop | Rotating residential | Local ISP addresses return IDR pricing and local promo states without triggering per-IP rate limits |
| App-surface data, TikTok Shop seller workflows, mobile web | Mobile (carrier) | Apps expect carrier IPs (Telkomsel, Indosat, XLSmart); mobile is expensive per GB but often the only thing that works |
| Logged-in seller back office, long multi-step checkout flows | Static residential / ISP | Same address across the whole session, so the platform doesn't see the login jump regions |
| Parsing data you already collected, open reference pages | Datacenter | Cheap, and the only category where cheapness doesn't cost you success rate |
| Streaming Indonesian TV or geo-blocked video | Residential, with rules checked first | Some providers restrict streaming on certain plan types |

The line that matters most for Indonesia: it's a mobile-first market, so a lot of what you'd normally do from desktop happens inside apps instead. Mobile proxies cost roughly $2 to $10 per GB depending on the provider, against roughly $1 to $8 per GB for residential. That price gap is why serious Indonesian operations usually run both rather than picking one.

## Where Indonesian IPs physically exist (this shapes everything)

Indonesia spans three time zones and more than 17,000 islands, but its network infrastructure does not. Consumer broadband is concentrated on Java, and the residential coverage you'll actually get sits in Jakarta, Surabaya, Bandung and Medan. If you need a residential exit in Kalimantan or Sulawesi, confirm availability before you buy, because supply there is thin everywhere, not just at one vendor.

The ISP mix also matters more than most buyers expect. Telkom IndiHome is the home broadband brand of state-owned Telkom, with the biggest subscriber base and the broadest reach, which makes it the closest thing to an average Indonesian household profile. Biznet and First Media are denser in upmarket Jakarta residential areas with better bandwidth quality. For account work, IndiHome-flavored addresses tend to be the safer match; for heavy scraping, Biznet and First Media connections hold up better under load.

If your target is TikTok Shop, one local detail is worth knowing. Indonesia suspended TikTok Shop in 2023 under social-commerce rules and only restored it after the platform merged with Tokopedia, which put seller and store systems through a migration. The practical consequence is stricter vetting of seller entities and login environments than in most markets, so binding a store to one fixed Indonesian address and keeping logins in the same city beats hopping between regions.

## What Indonesian proxies cost, by provider

Published rates vary by a factor of seven for what looks like the same product, so it's worth seeing the spread before you commit. The figures below are the rates these providers quote publicly as of 2026.

| Provider | Residential rate | Notes |
| --- | --- | --- |
| DataImpulse | $1/GB pay-as-you-go | Cheapest published entry point; mobile at ~$2/GB |
| SimplyNode | $4.00/GB down to $2.25/GB at volume | Indonesia pool quoted at ~1M IPs, sticky up to 6 hours |
| Bright Data | ~$4/GB promotional, ~$8 standard | Largest pool, managed scraping APIs priced per 1,000 results |
| NetNut | from $3.53/GB | ISP-residential static IPs around $7.99/GB |
| SOAX | $3.60/GB (Starter) | Unified credit across residential, mobile, ISP, datacenter |
| Decodo | $3.75/GB entry, ~$2 at 1TB+ | Sticky sessions up to 24 hours |
| Oxylabs | from $6/GB | Enterprise-focused, SLA-backed |
| IPRoyal | from $7.35/GB | Sticky sessions up to 7 days |
| Webshare | residential from $3.50/mo, datacenter from $2.99/mo | Free tier, cheapest datacenter option |

Two pricing models are hiding in that table, and they aren't comparable on one axis. Per-GB billing is right when each request uses very little data and you rotate constantly. Per-IP billing with unlimited bandwidth is right when your bandwidth per task is unpredictable or heavy, because your cost stops moving once you've bought the IPs.

That second model is where 9Proxy sits.

## 9Proxy's three models, and which one fits Indonesian work

9Proxy runs a residential-only network of 20M+ IPs across 90+ countries, with targeting down to country, state, city, ZIP and ISP level, and it splits its product three ways: per-IP with unlimited bandwidth, per-GB with unlimited endpoints, and bundles that mix both. Third-party directory listings show Indonesia among its supported countries.

The company raised prices on its IP-based and bundle packages on June 1, 2026, its first adjustment since launch, and left GB pricing untouched. So the numbers below reflect the post-adjustment structure. Everything is a prepaid balance top-up in USD rather than a monthly subscription, and unused IPs don't expire until you activate them.

### IP-based packages (unlimited bandwidth per IP)

| Package | Price | Effective rate | Get it |
| --- | --- | --- | --- |
| 100 IPs | $24 | $0.24/IP | Start with the 100-IP package |
| 500 IPs | $72 | $0.144/IP | Grab the 500-IP package |
| 1,000 IPs + 500 bonus | $126 | $0.084/IP | Get 1,500 IPs for $126 |
| 2,500 IPs | $210 | $0.084/IP | Buy the 2,500-IP tier |
| 5,000 IPs | $360 | $0.072/IP | Scale to 5,000 IPs |
| 15,000 IPs | $720 | $0.048/IP | Order 15,000 IPs |
| 25,000 IPs | $863 | $0.035/IP | Pick the 25,000-IP package |
| 50,000 IPs | $1,438 | $0.029/IP | Go for 50,000 IPs |
| 100,000 IPs | $2,300 | $0.023/IP | Buy the 100,000-IP business tier |
| 200,000 IPs | $4,140 | $0.021/IP | Order 200,000 IPs |
| 500,000 IPs | $8,625 | $0.018/IP | Get the 500,000-IP enterprise tier |

Each activated IP lives a few hours up to about 24 hours. There's no natural rotation in this model, so you either manage rotation yourself through the Auto Rotation feature on selected ports, or reuse an IP for free within 24 hours via the Today List as long as it's still online. This model requires the 9Proxy desktop app for local port forwarding.

### GB-based packages (180-day validity, unlimited endpoints)

| Package | Price | Rate | Get it |
| --- | --- | --- | --- |
| 5 GB | $15 | $3.00/GB | Try 5 GB first |
| 50 GB + 5 GB bonus | $105 | $2.10/GB | Take the 55 GB pack |
| 100 GB | $150 | $1.50/GB | Buy 100 GB |
| 200 GB | $200 | $1.00/GB | Order 200 GB |
| 1,000 GB | $800 | $0.80/GB | Get 1,000 GB |
| 2,000 GB | $1,500 | $0.75/GB | Scale with 2,000 GB |

The rate keeps sliding past 2,000 GB and bottoms out at $0.68/GB at the 10,000 GB tier. Enterprise GB packages carry unlimited validity instead of the standard 180 days and add team mode with one owner plus up to five members, per-member traffic controls and activity logs.

GB-based plans work straight from the dashboard with no app install: username/password authentication or IP whitelisting, sticky or rotating sessions, and you can generate as many endpoints as your balance allows.

### Bundle packages (IPs + traffic, traffic valid 180 days)

| Bundle | Contents | Price | Get it |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | Pick the Starter bundle |
| Popular | 1,500 IPs + 50 GB | $180 | Choose the Popular bundle |
| Pro | 5,000 IPs + 500 GB | $720 | Take the Pro bundle |

## Mapping plans to real Indonesian work

For a single Shopee category sweep from desktop, 5 GB is usually enough to learn what the endpoint looks like and how much data a page costs you. Most people who track a few hundred listings daily land in the 50 to 200 GB range, which at 9Proxy's rates runs $105 to $200 for 180 days of validity. That's hard to beat on per-GB billing: 200 GB at $1.00/GB against a $3.53/GB provider is $200 versus $706 for the same volume.

Where per-IP wins is multi-account and session work. Running a handful of seller operations or browser profiles where each needs a stable identity and might pull heavy bandwidth is exactly the case per-IP was built for. At the entry tier, $24 for 100 IPs with unlimited traffic means you don't sit there watching a bandwidth gauge while doing your job.

<blockquote>Running Indonesian app-surface work, including anything that lives inside TikTok Shop or a marketplace app? 9Proxy doesn't sell mobile carrier IPs. Its network is residential only, with no datacenter or ISP-static line either. For app-only endpoints you'd need a provider with a mobile pool, and it's worth pairing that with 9Proxy's GB plans for the desktop side rather than forcing one vendor to do both.</blockquote>

For a team mixing daily desktop sweeps with a few stable identities, the bundles price the combination below buying separately. On the Popular bundle, 1,500 IPs plus 50 GB for $180 is roughly $30 more than the IP tier alone while adding 50 GB of rotating traffic.

## Setting it up for Indonesia

1. Create an account and top up your balance. The sign-up flow uses a referral code, and crypto payments get an automatic 5% IP bonus on top, which is a real discount if you already hold stablecoins. 👉 Open the 9Proxy sign-up page to register.
2. Choose your model. IP-based if you need stable identities and heavy traffic; GB-based if you're rotating wide across many targets.
3. In the Proxy Generator, set the location filter to Indonesia, then narrow to state, city or ISP if your target platform localizes by region. Compare Jakarta against Surabaya before scaling: the two return different SERP and pricing states often enough to matter.
4. Pick session behavior. Rotating for broad price and category sweeps, sticky when a flow involves a login or a multi-step checkout that must not change address mid-way.
5. Authenticate with username/password (cleaner for cloud tools and scripts) or whitelist your device IP and skip credentials entirely.
6. Export your endpoint list as `.txt` or `.csv`, or copy the ready-made code samples from the dashboard, and run it against your real target. Test 20 to 50 requests before you scale: success rate on Shopee Indonesia is the only number that should drive how much you buy.

## What to check before you pay

Third-party reviews of 9Proxy describe a pattern worth knowing about. The recurring complaint isn't quality, it's the refund terms, which are narrow: credit refunds essentially cover IPs that die within about 60 seconds. There's no clearly advertised free trial, so in practice you're buying before you can fully validate the IPs against your own targets. A limited trial is offered to new users from time to time depending on availability, and it's worth asking support which type you'd get.

Second, the Acceptable Use Policy on IP-based plans no longer supports media streaming, so if your Indonesian work involves video platforms, confirm the current terms before purchasing rather than assuming.

Third, pool-size claims around this provider diverge widely. Figures from around 9 million to 95M+ IPs circulate, and the most consistently corroborated number across independent 2025 and 2026 reviews is the 20M+ across 90+ countries that the vendor publishes. Treat it as an advertised figure rather than a measured one, along with the vendor's stated 99.5% success rate, ~0.6s average response time and 99.95% uptime.

Fourth, uptime isn't flawless. Some users reported a service interruption in mid-2026, and reseller channels subsequently listed the IP proxies as restored and working. It's a young provider with a short track record relative to the enterprise players, which is roughly the trade-off you're accepting for the price gap.

## Is using proxies for Indonesian market work legal?

Public read-only collection of product prices, availability and rankings is where most Indonesian price-intelligence and SEO teams operate, and it's broadly acceptable. The line that has moved is personal data: Indonesia's Personal Data Protection Law (UU PDP, Law No. 27/2022) came into force with a two-year transition that ended in October 2024, meaning it's now fully enforceable. Penalties run up to 2% of annual revenue. Enforcement currently sits with Komdigi's directorate general for digital space oversight while the dedicated supervisory authority is still being built out, with an operational target in 2026.

For a Shopee price feed that captures listing prices and stock states, that framework doesn't change much. For anything touching personal data, it does, and it's worth reading properly rather than skimming.

## FAQ

**How many Indonesian IPs do I need for Shopee price tracking?**
Fewer than most people buy. Shopee Indonesia rate-limits by address rather than blocking outright, so rotation frequency matters more than pool size. Start with a GB package and let actual consumption tell you the volume before committing to an IP tier.

**Do I need city-level targeting, or is country enough?**
Country-level covers most work. Add city targeting when pricing, fulfilment or SERP results differ by region, which they do across Jakarta, Surabaya and Bandung often enough to justify it.

**Can 9Proxy do TikTok Shop Indonesia?**
Its residential proxies can reach TikTok Shop's web surface, but the app-side workflows that dominate Indonesian social commerce generally expect mobile carrier IPs, which this provider doesn't offer. Plan for two providers if that's your main target.

**Do unused IPs expire?**
No. IP-based packages sit in your balance until you activate them. GB packages carry 180-day validity, unlimited on Enterprise.

**What's the cheapest way to test whether it works for my target?**
The 5 GB GB-based pack at $15. Run it against your actual endpoint for a day before buying anything larger. 👉 Start with the 5 GB package and test against your own targets.
