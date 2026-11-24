# Review notes for the ads policy drafts (delete before publishing)

Branch draft/ads-policy, unpublished. wire-rewarded-ads task 6.4. Publish only right before the first Play upload of
a build with ads, together with the Play declarations (advertising ID, Data safety, contains ads).

## Questions for the user

1. **"Do not consent" button.** The AdMob GDPR message has Consent and Manage options, but no "Do not consent" on the
   first screen. The CNIL expects refusing to be as easy as accepting, and has fined sites over it. Turning it on is
   an AdMob console switch (no app update). Your decision; the policy text is the same either way.
2. **Effective date.** Fill in `[DATE OF THE FIRST RELEASE WITH ADS]` (EN) and
   `[DATE DE LA PREMIÈRE VERSION AVEC PUBLICITÉS]` (FR) on the four pages at publish time.
3. **Ad placements named in the policy.** The privacy page lists the three offers (double a level's gems, continue
   after a game over, get a booster). If change 3 ships a different set, the text follows it.

## What changed against the live pages

- Privacy: rewarded ads by Google AdMob (data, purposes, partners, Google as independent controller, Android ad
  settings); consent in the EEA, UK and Switzerland for ads and game statistics, changeable in Privacy options;
  game statistics on by default elsewhere; ad revenue measured with Firebase; crash reports always on; the 16+
  audience; legal bases split (consent / legitimate interest); "no ads" and "no advertising ID" removed.
- Terms: rewards from ads have no monetary value; the Rewarded ads section (optional, granted after a full watch,
  none on early close, failure or a kill, ad content belongs to advertisers); no automated or invalid ad activity.
- noindex is kept on all four pages.
