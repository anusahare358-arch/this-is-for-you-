# Photos + Music Fixed 💖

Is version mein saari 9 original photos, trimmed Enna Sona, styling aur JavaScript **index.html ke andar embedded** hain.

## GitHub / Vercel par update

1. ZIP ko **Extract / Unzip** karo.
2. Apni GitHub repository ka purana **index.html** replace karke is ZIP ka **index.html** upload karo. Naya index.html lagbhag 7.4 MiB ka hai; upload complete hone do.
3. Saath mein **vercel.json** bhi upload karo aur changes commit karo.
4. Vercel par us repository ka deployment complete hone do, phir live URL kholo aur refresh karo.

Vercel settings: **Framework Other**, **Build Command empty**, **Install Command empty**, **Output Directory .**. Root Directory wahi folder hona chahiye jisme index.html hai. vercel.json mein ye settings included hain.

GitHub Pages ke liye **Settings → Pages → Deploy from a branch → main → /(root) → Save**. `.nojekyll` bhi included hai.

## Phone par photos aur music

- ZIP ke andar preview kholne ki jagah pehle extract karo. Sabse achha test normal Chrome/Safari mein deployed website ke URL se karo.
- Saari 9 photos HTML mein hain. Gallery swipe karke har photo dekho; tap par full photo khulti hai.
- **Open my heart**, upar **Play music**, ya Enna Sona ke player ka **Play** button tap karo.
- Song ke pehle 10 seconds cut hain, aur song loop par hai. Phone ka media volume on rakho.
- Music permission fail ho toh **Tap to retry** se dobara chala sakte ho.
- Email reply sending remove hai. Share my answer visitor apni marzi se use kar sakta hai.

## Checks

ZIP integrity, embedded photos/music, original media bytes, script syntax aur music retry/pause flow check kiye gaye hain. Tumhare external deployed URL ka browser test nahi kiya gaya, kyunki uska link available nahi tha.

## Official setup guides

- https://vercel.com/docs/builds/configure-a-build
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
