**1. Introduction**

**1.1 About Flaer, Inc.**

This Privacy Policy explains how Flaer, Inc., a Delaware C-Corporation
("Flaer," "we," "us," or "our"), collects, uses, stores, shares, and
protects personal information when you use our mobile applications,
website, and related services. Our registered address is: 251 Little
Falls Drive, Wilmington, DE 19808, USA.

Flaer operates two applications:

-   Flaer (Customer App) --- for individuals who connect their Instagram
    account, post content, and earn insights-based rewards.

-   Flaer for Advertiser (Flaer Ads) --- for businesses who want to be
    shared by their customers, want to view aggregated insights of those
    shares, and purchase credits so they can be discoverable and
    participate in the Flaer ecosystem.

This Privacy Policy applies to both applications and all backend systems
that support them.

**1.2 Purpose of This Privacy Policy**

This Privacy Policy describes the types of information we collect, how
we use and share this information, how we protect it, and what rights
and choices you have. It also explains how Instagram data, advertiser
data, rewards, referrals, withdrawals, and account deletion are handled.

**1.3 Scope of This Privacy Policy**

This Privacy Policy applies to:

-   the Flaer Customer App,

-   the Flaer Ads (Advertiser) App,

-   the Flaer website (flaer.app), and

-   all related backend services, APIs, integrations, and storage
    systems.

This includes all interactions involving Instagram data, advertiser
business information, rewards, referrals, notifications, geolocation
discovery, withdrawals through Stripe, and all other features documented
in Flaer's technical flows.

**1.4 Definitions**

-   **"User"** --- an individual using the Customer App to post content,
    earn rewards, or withdraw earnings.

-   **"Advertiser"** --- a business or representative using Flaer Ads to
    view aggregated insights from customer shares and purchase credits.

-   **"Instagram Data"** --- information retrieved through the Instagram
    Graph API, including media, insights, profile data, and tokens.

-   **"Monetized Content"** --- Instagram posts or stories that qualify
    for rewards.

-   **"Services"** --- all features of the Customer App, Advertiser App,
    backend systems, and website.

**1.5 Age Requirements**

You must be at least 13 years old to use Flaer. If you are under the
legal age in your country to manage a payout method, your parent or
legal guardian must approve your use of the withdrawal features. Flaer
does not knowingly allow children under 13 to use its Services.

**1.6 Contact Information**

Flaer, Inc. 251 Little Falls Drive Wilmington, DE 19808, USA Email:
legal@flaer.app

**2. Data We Collect**

We collect information from Users and Advertisers to operate the Flaer
Customer App, the Flaer Ads App, and our backend services.

We only collect the data categories described below. We do not collect
any information that is not explicitly listed.

**2.1 Information You Provide to Us**

**2.1.1 Account Registration (Users & Advertisers)**

When you create an account, you provide:

-   Email address

-   Password (Advertisers)

-   Full name (Users)

-   Business name (Advertisers)

-   Optional: gender (Users)

-   Optional: year of birth (Users)

-   Optional: personal interests (Users)

This information is required to create and manage your account.

**2.1.2 Instagram Login (Users)**

When you connect your Instagram account through the Instagram Graph API,
you authorize Flaer to access specific Instagram Data (listed in Section
2.3). We do not receive your Instagram password.

**2.1.3 Withdrawal Information (Users)**

When you connect a Stripe Connect account, you provide:

-   Stripe Connect account ID

We do not store bank account numbers, card numbers, identity documents,
or government IDs. These are provided directly to Stripe.

**2.1.4 Advertiser Business Information (Flaer Ads)**

Advertisers provide:

-   Business name

-   Business description

-   Business address

-   Business category

-   Business images (stored on AWS S3)

This information is used to power business discovery and the advertiser
profile.

**2.1.5 Ratings and Reports (Advertisers)**

When Advertisers review content shared about their business, they may:

-   rate the share (positive/neutral/negative),

-   submit a report (for inappropriate, misleading, or invalid content).

These ratings and reports are stored internally and associated with the
share.

**2.1.6 Referral Codes (Users & Advertisers)**

When you use or create a referral code, we store:

-   the referral code,

-   which account generated it,

-   which account used it.

This allows referral attribution and referral rewards.

**2.2 Information We Collect Automatically**

**2.2.1 Device Information**

We only collect the minimal technical identifiers needed for app
functionality:

-   push notification token (if notifications enabled)

We do not store IP addresses, advertising identifiers, device IDs, or
device metadata in our own database.

**2.2.2 Functional and Operational Data**

We collect limited operational events such as:

-   login attempts and results

-   token refresh events

-   content submission events

-   reward estimation and reward finalization events

-   withdrawal requests and statuses

-   share rating events

-   advertiser reports

-   share creation and payout events

These events allow us to operate core platform features and maintain
reliability.

**2.3 Information We Collect From Instagram (Users)**

When you connect your Instagram account, Flaer receives the following
Instagram Data depending on the permissions you grant.

**2.3.1 Basic Instagram Account Information**

We may collect:

-   Instagram user ID

-   Instagram username

-   Profile picture URL

-   Account type (Creator or Business)

-   Follower count

-   Aggregated follower location summaries (if provided by API)

We do not collect private messages or follower identities.

**2.3.2 Media Information (Posts & Stories)**

For media you choose to monetize, we collect:

-   Media ID

-   Media URL (used to generate a compressed media copy stored on AWS
    S3)

-   Thumbnail

-   Post timestamp

-   Metadata such as media type (photo/video)

We store a compressed copy of the media on AWS S3 and retain it until
you delete your account or submit an Instagram Data Deletion Request.
Media is not deleted when you remove it from Instagram.

**2.3.3 Instagram Insights (Posts & Stories)**

For monetized content, we collect insights such as:

**Posts:**

-   impressions

-   reach

-   likes

-   comments

-   saves

-   shares

-   video views (if applicable)

**Stories:**

-   impressions

-   reach

-   taps forward

-   taps back

-   exits

-   replies

-   link clicks (if provided by the API)

We store insights until your account is deleted or an Instagram Data
Deletion Request is submitted.

**2.3.4 Instagram Tokens**

We store:

-   long-lived access token

-   token expiration time

Tokens let Flaer retrieve authorized data. They are deleted when you
disconnect Instagram or delete your account.

**2.4 Information We Collect From Advertisers (Flaer Ads)**

**2.4.1 Business Profile Data**

We collect:

-   business name

-   description

-   category

-   address

-   business images (stored on S3)

**2.4.2 Business Location & Discovery Data**

We send the business postal address to LocationIQ to receive:

-   latitude and longitude

Only advertiser data is sent. User GPS is never stored or transmitted to
LocationIQ.

**2.4.3 Credits & Purchases**

We store:

-   amount of credits purchased

-   purchase timestamps

-   Stripe Payment Intent ID

-   resulting credit balance

-   locked credit amounts (when share created)

We do not store any card or billing details.

**2.4.4 Viewing Customer Shares**

For each monetized share, advertisers can see:

-   the media content

-   posting timestamp

-   monetization timestamp

-   insights of an individual share (reach, interactions, views, and
    similar)

-   aggregated insights across all shares

-   aggregated metrics:

    -   total shares

    -   total reach

    -   average price per share

    -   unique customers (count only, no identities)

Advertisers can never see:

-   user identity

-   username

-   user profile

-   who viewed the content

-   any other personal data

Each share appears as an individual anonymous item.

**2.5 Information We Receive From Third Parties**

**2.5.1 Stripe**

We receive:

-   Stripe Connect account ID

-   payout and payment statuses

-   transaction timestamps

-   transaction amounts

Stripe may collect country, IP address, and identity information when
required by law, but this never reaches Flaer's database.

**2.5.2 Appsflyer**

Appsflyer may collect:

-   device identifiers

-   IP address

-   install metadata

-   referral link information

-   deep-link routing data

Flaer uses this data only for referral attribution, not advertising.

**2.5.3 LocationIQ**

We receive:

-   geographic coordinates

Only advertiser business addresses are sent, never User data.

**2.5.4 Email Provider**

Our email provider receives:

-   email address

-   email content

Used strictly for account and security communication.

**2.6 Information We Do Not Collect**

We do not collect or store:

-   user IP addresses

-   payment card numbers

-   bank account numbers

-   biometric data

-   GPS location of users

-   continuous location history

-   contact lists

-   messages or private communications

-   facial data

-   advertising identifiers

-   browsing history

-   cross-app tracking data

-   demographic details beyond what Instagram API provides in aggregated
    form

We do not create or sell User identity graphs.

**3. How We Use Your Data**

We use the information we collect to operate the Flaer Customer App, the
Flaer Ads App, support monetization and withdrawals, maintain platform
integrity, comply with legal obligations, and improve core
functionality. We do not use your data for advertising, data selling, or
profiling outside of what is required to operate these services.

**3.1 Operating the Flaer Customer App (Users)**

**3.1.1 Instagram Connection and Access**

We use your Instagram authorization to:

-   connect your Instagram account,

-   retrieve permitted Instagram Data,

-   maintain long-lived access tokens,

-   reauthenticate when required,

-   process media and insights for monetization.

We do not access private messages, follower identities, or any data
beyond what you explicitly authorize.

**3.1.2 Content Monetization & Reward Processing**

We use your media, insights, and timestamps to:

-   validate whether a post or story is eligible for monetization,

-   calculate estimated rewards,

-   lock advertiser credits based on the estimated reward,

-   calculate final rewards after the required visibility period (7 days
    for posts, 23 hours 45 minutes for stories),

-   release any leftover locked credits back to the advertiser.

If content is removed from Instagram before payout is finalized:

-   it becomes ineligible for reward,

-   locked advertiser credits are unlocked,

-   the share remains stored but unpaid.

We store both the estimated reward and the final reward and the
parameters required to reproduce the final calculation.

**3.1.3 Displaying Monetized Shares to Advertisers**

When your content is monetized, we use your media and metadata to
display:

-   the content you shared,

-   the posting timestamp,

-   the monetization timestamp,

-   insights of an individual share (reach, interactions, views, and
    similar)

-   aggregated performance metrics across all Users who shared that
    business.

Each monetized submission is shown as an individual anonymous share.

Advertisers cannot see:

-   your identity,

-   your username,

-   your IG profile,

-   your follower list,

-   who viewed your content.

Advertisers can rate or report a share, and this rating/report is stored
internally.

**3.1.4 Withdrawals & Payouts**

We use your Stripe Connect account ID to:

-   validate payout eligibility,

-   send your earnings to Stripe,

-   process withdrawal requests,

-   maintain payout history.

We do not store bank account numbers, card details, or identity
documents.

**3.1.5 Notifications**

We use your push token and email to notify you about:

-   monetization confirmations,

-   insight availability,

-   reward updates,

-   payout status changes,

-   required account actions,

-   security and system alerts.

We do not send unrelated marketing notifications without your consent.

**3.1.6 Referrals**

We use referral codes to:

-   attribute referrals to the correct User or Advertiser,

-   apply bonuses,

-   route deep links to the correct account.

We do not reveal identities between referrers and referees.

**3.2 Operating the Flaer Ads App (Advertisers)**

**3.2.1 Business Profile & Discovery**

We use your business information to:

-   create your public business profile,

-   display your business to Users,

-   enable in-app discovery based on address,

-   convert your address into coordinates through LocationIQ.

We do not store or use User GPS coordinates.

**3.2.2 Credits, Purchases, and Locked Balances**

We use your credit purchases and Stripe confirmations to:

-   maintain your credit balance,

-   lock credits when a User monetizes a share,

-   release leftover credits after final reward calculation,

-   prevent monetization attempts when you lack sufficient credits.

If you do not have enough credits to cover the estimated reward:

-   the User's share cannot be monetized,

-   the share creation fails,

-   no media or insights are stored.

**3.2.3 Viewing Customer Shares & Insights**

We use User shares to allow Advertisers to view:

-   each individual shared media item,

-   posting timestamp,

-   monetization timestamp.

We also use aggregated data to show:

-   total shares,

-   total reach,

-   average price per share,

-   unique customers (count only, never identities),

-   aggregated insights across all shares.

We do not show any identifying information about Users.

**3.2.4 Share Ratings & Reports**

When Advertisers rate or report a share:

-   we store the rating or report,

-   we use this information to improve content verification and platform
    safety.

These ratings/reports never reveal User identity.

**3.3 Security, Integrity & Compliance**

**3.3.1 Fraud Detection & Abuse Prevention**

We use media data, insights, timestamps, and share metadata to detect:

-   invalid content,

-   manipulated engagement,

-   repeated or duplicate submissions,

-   suspicious monetization activity,

-   attempts to circumvent platform rules.

We store:

-   share ratings,

-   advertiser reports,

-   internal moderation statuses where applicable.

We do not create behavioral profiles or risk scores beyond operational
requirements.

**3.3.2 Security & Authentication**

We use login information, token lifecycle data, and minimal operational
logs to:

-   maintain secure sessions,

-   protect user accounts,

-   detect unauthorized access,

-   ensure proper functioning of authentication flows.

We do not store IP addresses in the Flaer database.

**3.3.3 Legal, Regulatory & Platform Compliance**

We use data to comply with:

-   Instagram Platform Policies,

-   Stripe payout and financial verification rules,

-   tax and accounting requirements,

-   valid legal requests,

-   platform integrity requirements from app stores.

We only disclose the minimum data necessary for compliance.

**3.4 Platform Reliability & Improvement**

We use functional diagnostics such as:

-   login event results,

-   token expiration behavior,

-   reward computation events,

-   withdrawal statuses,

-   share creation events,

-   rating and reporting events,

to maintain system reliability, detect issues, and improve core
features.

Attribution data from Appsflyer is used only to support referral flows
and does not contribute to advertising or tracking profiles.

**3.5 What We Do Not Use Your Data For**

We do not use your data for:

-   targeted advertising,

-   selling or renting data to third parties,

-   data brokering,

-   cross-app tracking,

-   behavioral profiling,

-   revealing User identities to Advertisers,

-   automated decision-making beyond reward computation,

-   storing or processing User GPS data.

**4. How We Share Your Data**

We do not sell personal data. We only share information when it is
necessary to operate the Flaer Customer App, the Flaer Ads App, comply
with the law, or support essential third-party integrations. We never
share User identities with Advertisers.

**4.1 Service Providers**

We share limited data with trusted service providers who help us operate
core platform features. They receive only the information required to
perform their services and must protect it under strict contractual
privacy obligations.

**4.1.1 Meta / Instagram**

We share requests with Instagram to:

-   authenticate your login,

-   refresh access tokens,

-   deauthorize access when requested,

-   retrieve Instagram Data you explicitly permit.

We do not share any other personal data with Instagram.

**4.1.2 Stripe (Payments & Withdrawals)**

Stripe receives:

-   Stripe Connect account ID,

-   payment/payout amounts,

-   timestamps,

-   transaction statuses.

Flaer never receives or stores:

-   credit card numbers,

-   bank account numbers,

-   government IDs,

-   any sensitive financial information.

Stripe may collect additional information directly from you for identity
verification and legal compliance.

**4.1.3 Amazon Web Services (AWS)**

AWS hosts the infrastructure supporting Flaer. AWS stores:

-   compressed copies of User media for monetized shares,

-   business images,

-   database information required for platform operation.

AWS does not access your data except as required for maintenance and
security.

**4.1.4 Appsflyer**

Appsflyer processes:

-   referral attribution,

-   install attribution,

-   deep-link routing.

Appsflyer may receive:

-   IP address,

-   device identifiers,

-   install metadata,

-   referral link data.

This data is used only for referral and deep-link functionality. It is
never used for advertising or tracking profiles by Flaer.

**4.1.5 LocationIQ (Advertiser Business Addresses)**

We send the Advertiser's business postal address to LocationIQ to
receive:

-   geographic coordinates,

User personal data and User GPS are never shared with LocationIQ.

**4.1.6 Email Delivery Provider**

Our email provider receives:

-   your email address

-   email content

solely to send verification emails, security alerts, and essential
account messages.

**4.2 Sharing with Advertisers (Users)**

Advertisers never receive personal information about Users.

For each monetized share, Advertisers can see:

-   the media content (image or video),

-   the timestamp the content was posted,

-   the timestamp the content was monetized in Flaer,

-   insights of an individual share (reach, interactions, views, and
    similar)

-   aggregated performance totals across all Users who shared their
    business, including:

    -   total shares,

    -   total reach,

    -   average price per share,

    -   unique customers (count only, no identities).

Advertisers cannot see:

-   your name,

-   your username,

-   your Instagram profile,

-   follower information,

-   who viewed your content,

-   your profile picture,

-   your account details,

-   your location,

-   any personally identifying information.

Each share appears as an individual, anonymous item inside the
advertiser dashboard.

**4.3 Sharing with Other Users**

We do not share your personal information with other Users. The platform
does not include a public profile, feed, or any user-to-user visibility.

**4.4 Legal, Regulatory & Safety Purposes**

We may share information when required to:

-   comply with applicable laws,

-   respond to lawful requests such as subpoenas or court orders,

-   resolve disputes involving payments or withdrawals,

-   detect, prevent, or investigate fraud or abuse,

-   protect the safety, rights, or property of Users, Advertisers, or
    Flaer,

-   enforce our Terms of Service.

We limit disclosure to the minimum amount necessary.

**4.5 Business Transfers**

In the event of a merger, acquisition, corporate restructuring, or sale
of assets, personal data may be transferred to a successor entity. Any
successor will be required to uphold this Privacy Policy or adopt a
policy offering equal or greater protection.

**4.6 With Your Consent**

We may share information for purposes not listed above if you provide
explicit consent. Consent is always optional and can be revoked at any
time.

**5. Monetization and Insights Processing**

This section explains how Flaer processes User content, Instagram
insights, rewards, and advertiser credits. It also describes when
insights are collected, how rewards are calculated, what Advertisers can
see, and when content becomes ineligible for payment. Flaer never
reveals User identities to Advertisers, never sells data, and never uses
insights for advertising or profiling.

**5.1 Content Submission and Share Creation**

When a User shares content about a business on Instagram and selects it
for monetization in Flaer:

-   retrieves the media file from Instagram,

-   creates a compressed copy stored on AWS S3,

-   stores the posting timestamp,

-   stores the monetization timestamp,

-   assigns a unique share ID,

-   computes the estimated reward,

-   verifies that the Advertiser has enough available credits.

A share is created only if the Advertiser has sufficient credits to
cover the estimated reward. If not, the User sees a message such as "Not
shareable --- this business ran out of budget." In that case, no share
is created, and no data is processed.

**5.2 Credit Locking (Advertisers)**

When a share is created:

-   Flaer immediately locks credits from the Advertiser's balance equal
    to approximately 1.5× the estimated reward.

-   These credits remain locked until the final reward is calculated.

-   After the final reward is determined, any leftover locked credits
    are released back to the Advertiser.

Locked credits ensure that the Advertiser has sufficient funds to cover
the estimated payout.

Advertisers can see:

-   estimated reward,

-   locked credit amount,

-   final reward after the 7-day/23h 45m period,

-   unlocked leftover balance.

**5.3 Insight Collection (Instagram)**

Flaer fetches Instagram insights only once, at the end of the required
period:

-   7 days for posts

-   23 hours 45 minutes for stories

We do not continuously fetch insights. We do not re-fetch insights after
the final reward is computed. We do not request insights more than once
per monetized share.

At the insight-fetch time, Flaer retrieves only the metrics required to:

-   validate engagement,

-   calculate the final reward,

-   detect content removal,

-   store performance data for the Advertiser (in aggregated form).

All insights are stored permanently until:

-   the User deletes their account, or

-   the User submits an Instagram Data Deletion Request.

**5.4 Reward Calculation (Estimated and Final)**

**5.4.1 Estimated Reward**

When the User submits a share, Flaer calculates the estimated reward
using:

-   business settings,

-   category-based pricing,

-   internal multipliers (locked at creation),

-   anonymized historical performance patterns.

Advertisers can see the estimated reward immediately.

**5.4.2 Final Reward**

After the required visibility period ends (7 days for posts, 23 hours 45
minutes for stories), Flaer:

-   fetches insights from Instagram,

-   calculates the final reward using stored multipliers/factors,

-   stores the final reward permanently.

Final reward is never recalculated once computed. Multipliers are stored
for:

-   transparency,

-   internal audit,

-   future algorithm tuning (not retroactive).

Advertisers can see the final reward after processing.

**5.5 When Shares Are Not Rewarded**

A share becomes unrewarded when Flaer cannot access Instagram insights
or confirm eligibility at the end of the period. Flaer does not classify
these as "invalid," but they result in no final payment.

A share is unrewarded if:

-   the User deletes their Instagram post before insight collection,

-   the User deletes their Flaer account,

-   the User revokes Instagram permissions,

-   the User submits an Instagram Data Deletion request,

-   Instagram access tokens expire and cannot be refreshed.

In these cases:

-   the final reward is set to null,

-   locked credits are unlocked,

-   the share remains stored for audit and advertiser history,

-   no payout occurs.

Flaer does not delete S3 media, insights, or metadata unless the User
requests data deletion or deletes their account.

**5.6 Fraud Prevention and Business Reporting**

Flaer does not perform automated fraud analysis or automated content
rejection.

Only Advertisers may:

-   report a share,

-   flag inappropriate or misleading content,

-   rate the share.

Flaer stores these:

-   ratings,

-   reports,

-   timestamps of when they were submitted.

These do not affect reward calculation unless the User's content is
deleted from Instagram or becomes inaccessible during insight
collection.

Flaer may use these reports to:

-   debug issues,

-   review repeated abusive patterns,

-   comply with legal or platform requirements.

Flaer does not build behavioral profiles or automated risk scores.

**5.7 What Advertisers Can See**

Advertisers see:

**Per-share information:**

-   media content (image or video),

-   posting timestamp,

-   monetization timestamp,

-   estimated reward,

-   locked credit amount,

-   final reward

-   insights of an individual share (reach, interactions, views, and
    similar)

**Aggregated information (across ALL Users):**

-   total shares,

-   total reach,

-   average price per share,

-   unique customers (count only),

-   combined engagement metrics.

**Advertisers NEVER see:**

-   usernames,

-   names,

-   profile pictures,

-   IG profile details,

-   viewer details,

-   follower lists,

-   any personal User information.

Each share appears as an individual anonymous item.

**5.8 Payouts to Users**

Final rewards are added to the User's Flaer balance after processing.
Users may withdraw their balance via Stripe Connect. Stripe may require
identity verification. Flaer never receives identity documents or
financial account numbers.

Payouts are:

-   non-refundable,

-   logged in Flaer's internal ledger,

-   stored in Stripe for compliance.

If a User deletes their account before payout is triggered:

-   all User data is deleted (except mandatory financial records),

-   unpaid rewards are forfeited,

-   locked credits return to the Advertiser.

**5.9 Monetization Rules Transparency**

Flaer discloses:

-   how rewards are calculated,

-   when insights are fetched,

-   when shares become ineligible,

-   how advertisers see aggregated performance,

-   retention and deletion rules for insights and media.

No algorithmic decisions are made beyond reward calculation.

Flaer does not use:

-   machine learning profiling,

-   behavioral scoring,

-   location-based risk checks,

-   automated content rejection.

**5.10 No Resale or Reuse of Insights**

Insights collected for monetization:

-   are used ONLY for reward calculation,

-   may be shown to Advertisers only in aggregated form,

-   are never shared with third parties beyond service providers,

-   are never used for advertising or personalization.

Flaer does not sell or rent User insights.

**6. Cookies, Tracking, and Similar Technologies**

Flaer does not use cookies, web beacons, pixel tags, or similar tracking
technologies inside the mobile applications. We do not use technologies
that track your behavior across other apps or websites.

**6.1 Cookies on Our Website**

The Flaer website (flaer.app) uses only:

-   essential cookies required for security and basic operation, and

-   optional analytics cookies (if enabled) such as simple page
    statistics.

These cookies do not track your browsing across other sites and are not
connected to your Flaer account. You may control or block cookies
through your browser settings.

**6.2 No Cross-App or Cross-Site Tracking**

Flaer does not:

-   track you across other apps or websites,

-   use advertising identifiers for marketing,

-   create behavioral profiles for advertising,

-   perform retargeting or ad-based tracking,

-   link your Flaer activity to third-party apps.

Flaer uses no SDKs that collect cross-app data.

**6.3 Appsflyer (Attribution Only)**

Flaer uses Appsflyer exclusively for:

-   referral link attribution,

-   install attribution,

-   deep-link routing.

Appsflyer may collect device-level identifiers or IP addresses
independently, based on its own privacy policy. Flaer does not use
Appsflyer data for:

-   advertising,

-   profiling,

-   retargeting,

-   analytics beyond attribution.

Appsflyer data is not combined with User content, insights, or identity.

**6.4 No In-App Web Tracking**

The Flaer apps do not:

-   embed trackers inside media previews,

-   inject cookies into your Instagram activity,

-   use fingerprinting technologies,

-   store cookies inside the mobile app.

All data collected inside the apps is limited to:

-   operational events,

-   notifications tokens,

-   data you voluntarily provide,

-   Instagram data you authorize.

**6.5 Third-Party Websites**

If you visit third-party websites (such as Stripe or Meta) through links
in the app, their own cookies and tracking technologies may apply. These
are governed by their own privacy policies, not ours.

**7. Data Storage and Security**

Flaer uses modern security practices, AWS cloud infrastructure, and
industry-standard encryption to protect personal data. We implement
technical and organizational measures designed to protect User
information against unauthorized access, loss, misuse, or alteration.

**7.1 Cloud Infrastructure (AWS)**

All Flaer data is stored in Amazon Web Services (AWS) located in:

-   US East (N. Virginia) --- us-east-1

AWS provides:

-   physical data center security,

-   network firewalls,

-   controlled access facilities,

-   continuous monitoring,

-   compliance certifications (SOC 2, ISO 27001, etc.).

No data is stored outside AWS except when required to process:

-   Stripe payments,

-   Instagram Graph API requests,

-   Appsflyer referral attribution,

-   transactional email delivery.

Flaer does not store any data with third parties beyond those listed in
this Privacy Policy.

**7.2 Encryption at Rest**

All data stored by Flaer is encrypted at rest:

-   AWS RDS uses AES-256 encryption with AWS-managed keys.

-   S3 media assets (User-generated content, compressed media copies)
    use SSE-S3 encryption.

-   Instagram long-lived access tokens are encrypted using the Node.js
    crypto package before being written to the database.

This prevents unauthorized access even if disk-level data is
compromised.

**7.3 Encryption in Transit**

All communication between:

-   mobile applications,

-   Flaer's backend servers,

-   AWS infrastructure,

-   Stripe,

-   Instagram,

-   Appsflyer,

is protected by HTTPS/TLS 1.2+. We do not allow insecure HTTP
connections.

**7.4 Access Controls**

Access to production data is strictly limited.

Currently:

-   Only the CEO / lead developer has access to production systems.

In the future:

-   Access will remain limited to senior engineers only,

-   Protected by multi-factor authentication (MFA),

-   Logged through AWS CloudTrail.

No contractors or external parties have access to production data.

**7.5 Logging and Monitoring**

Flaer does not store internal backend logs containing personal data.

AWS provides infrastructure-level monitoring through:

-   CloudWatch,

-   CloudTrail,

-   AWS logging services.

These logs may include metadata such as service health, uptime, or
security alerts, but do not contain personal information.

Flaer does not store:

-   IP address logs,

-   location logs,

-   behavioral logs.

**7.6 Rate Limiting and Abuse Prevention**

To maintain platform integrity, the backend implements:

-   per-route rate limits,

-   per-IP throttling,

-   per-user request limits,

-   protections against brute-force attempts,

-   protections against API abuse.

These controls help prevent unauthorized access and misuse.

**7.7 Backups and Disaster Recovery**

Flaer performs automated backups through AWS RDS:

-   Daily automated backups

-   Retention period: 14 days

-   Stored in us-east-1

-   Restorable to specific points in time within the retention window

S3 objects benefit from AWS internal durability and redundancy. We do
not store replicated copies in other regions. Backups are encrypted and
protected by AWS security controls.

**7.8 No Local Storage of Sensitive Data**

Flaer does not store sensitive information on User devices except:

-   access tokens needed for authentication, stored securely by the
    operating system's protected storage.

We do not store:

-   credit card information,

-   banking credentials,

-   identity documents.

Stripe manages all sensitive financial data.

**7.9 Security Responsibilities**

While Flaer implements industry-standard safeguards, Users are
responsible for:

-   protecting their device,

-   securing their Instagram account,

-   choosing strong passwords for connected services,

-   not sharing authentication codes or tokens.

**8. Data Retention**

Flaer retains personal data only for as long as necessary to operate the
platform, comply with financial and legal obligations, resolve disputes,
and maintain accurate internal records. All retention periods below
reflect how the platform actually works.

**8.1 Instagram Data**

Media (S3)

We store a compressed copy of media you choose to monetize on AWS S3.
Media is retained permanently until one of the following happens:

-   you delete your Flaer account,

-   you request Instagram Data Deletion using the Instagram Data
    Deletion endpoint.

If the original Instagram post/story is deleted, we do not delete the S3
copy automatically. The share becomes unrewarded but stays stored for
audit and advertiser history.

Insights

Insights fetched from Instagram (impressions, reach, taps, exits, etc.)
are retained:

-   permanently,

-   until account deletion or Instagram Data Deletion request.

Instagram Tokens

Instagram access tokens are deleted immediately upon:

-   account deletion,

-   Instagram data deletion request,

-   Instagram deauthorization request.

**8.2 Flaer User Account Data**

When a User deletes their Flaer account, Flaer instantly deletes:

-   S3 media files

-   insights

-   share history

-   email

-   settings

-   notifications tokens

-   IG access tokens

-   all profile-related information

No delay, no 24-hour window --- deletion is immediate.

**Exceptions (required by law):** Flaer must retain:

-   Stripe payout logs

-   Flaer internal ledger events

-   transaction IDs

-   payout histories

-   credit/purchase logs

-   tax and accounting records

These remain for 5--7 years, depending on jurisdiction. They cannot be
tied back to the User once the account is deleted.

**8.3 Flaer Advertiser Account Data**

When an Advertiser deletes their account, Flaer deletes:

-   business profile

-   business images (S3)

-   contact information

-   advertiser settings

However:

-   Shares created by Users remain stored,

-   They remain fully anonymous,

-   They no longer reference the Advertiser account in any way.

This preserves:

-   User history

-   platform analytics

-   aggregated performance data

-   audit consistency

Shares never reveal User identity and remain safe for retention.
Financial records related to the Advertiser must be retained for legal
reasons (5--7 years).

**8.4 Monetized vs. Unrewarded Shares**

Monetized (Paid) Shares

Retained permanently until User account deletion or Instagram data
deletion.

Unrewarded Shares (final reward = null)

Retained permanently until User account deletion or Instagram data
deletion. A share becomes unrewarded if:

-   User deletes IG content early,

-   User deletes their Flaer account,

-   User revokes IG permissions,

-   Instagram tokens expire and cannot be refreshed,

-   insights cannot be retrieved at the required time.

Unrewarded shares are kept for audit history and advertiser aggregated
metrics.

**8.5 Financial Records (Mandatory Retention)**

Regardless of User or Advertiser deletion, Flaer is legally required to
retain:

-   Stripe payout records

-   transaction logs

-   credit purchase history

-   internal ledger entries

-   fee calculations

-   timestamps for financial activity

-   compliance logs required by payment regulations

Retention: 5--7 years (standard for U.S. corporate and tax regulations).
These records are decoupled from personal identity after account
deletion.

**8.6 Backups**

AWS RDS automated backups:

-   daily backup snapshots

-   retained for 14 days

-   stored in the us-east-1 region

-   encrypted at rest

-   deleted automatically after the retention window

Backups do not extend the retention of deleted User data beyond legal
financial records.

**8.7 Content Removed From Instagram**

If User removes content from Instagram:

-   Flaer does not delete stored media or insights immediately

-   the share becomes ineligible for reward

-   advertiser credits unlock automatically

-   the share remains stored and anonymized for platform integrity

This is compliant because the data was lawfully retrieved before
deletion.

**8.8 After Account Deletion**

Once a User deletes their account:

-   S3 media deleted instantly

-   insights deleted instantly

-   all share records deleted instantly

-   IG tokens deleted instantly

-   notification tokens deleted instantly

-   email deleted instantly

-   settings deleted instantly

Only mandatory financial records remain (Section 8.5).

**9. Your Rights and Data Deletion**

Users and Advertisers have rights regarding their personal data. Flaer
provides clear controls that allow individuals to access, delete, or
manage the information stored on the platform. We respond to all
privacy-related requests and maintain full compliance with applicable
laws, including GDPR, CCPA, and Meta's Data Deletion Policy.

**9.1 Right to Access**

Users and Advertisers may request:

-   a summary of personal data stored in Flaer,

-   categories of data collected,

-   the purposes for which data is used,

-   Instagram data currently linked to the account,

-   payout or credit history,

-   insight categories stored for monetized shares.

Requests may be submitted to legal@flaer.app. Flaer may require
verification to protect account integrity.

**9.2 Right to Delete Your Data**

Users may delete their Flaer account at any time through in-app
settings. When an account is deleted:

-   all S3 media is deleted instantly,

-   insights and share records are deleted instantly,

-   the IG access token is deleted instantly,

-   all referral and notification data is deleted,

-   User-side ratings and settings are deleted,

-   login data is deleted,

-   all personal identifiers are removed.

Only financial data that must be preserved by law (Section 8.5) is
retained.

Advertisers may also delete their account at any time. When an
Advertiser deletes their account:

-   business images and profile are deleted,

-   advertiser settings and metadata are deleted,

-   shares posted by Users remain stored but are fully anonymized and no
    longer tied to the business.

**9.3 Right to Correct Your Information**

Users and Advertisers may request corrections or updates to:

-   email address,

-   business name,

-   business description,

-   account information,

-   notification preferences.

For Instagram-linked fields, corrections require updating the
information directly through Instagram.

**9.4 Right to Revoke Instagram Permissions**

Users may revoke Instagram access at any time via:

-   the "Disconnect Instagram" option inside Flaer,

-   the Instagram Settings → Apps and Websites → Active tab,

-   the Instagram Data Deletion endpoint.

When Instagram permissions are revoked:

-   the IG access token is deleted,

-   future insight fetching becomes impossible,

-   shares awaiting rewards become unrewarded,

-   any locked advertiser credits are released,

-   all previously stored IG data is deleted according to the chosen
    deletion method.

**9.5 Instagram Data Deletion Request**

In compliance with Instagram Platform Policy, Users may request that
Flaer delete all Instagram-derived data by submitting a deletion request
through:

-   the in-app deletion flow, or

-   Instagram's official Data Deletion request page, or

-   an email to legal@flaer.app.

Upon receiving such a request, Flaer deletes:

-   media stored from Instagram,

-   insights from Instagram,

-   post metadata,

-   Instagram access tokens,

-   all shares associated with the Instagram account.

Financial records required by law remain stored as permitted.

**9.6 Right to Data Portability**

Users may request:

-   a copy of their payout history,

-   a record of their monetized shares (media is deleted on account
    deletion, so only metadata may be available),

-   a summary of insights stored.

Flaer provides data in machine-readable format whenever technically
feasible.

**9.7 Right to Restrict or Object to Processing**

Because Flaer processes data only:

-   with User consent,

-   for platform operation,

-   to fulfill monetization algorithms,

-   for advertiser reporting in aggregated form,

-   to comply with legal obligations,

Users may object to certain processing activities such as:

-   receiving notifications,

-   use of referral tracking,

-   storage of optional profile information.

These settings are controllable in-app or by contacting legal@flaer.app.

**9.8 Rights of California Residents (CCPA)**

California residents may request:

-   access to personal data,

-   deletion of personal data,

-   categories of data disclosed to third parties,

-   the right to opt-out of "sales" of data (Flaer does not sell
    personal data),

-   equal service regardless of exercising privacy rights.

Requests may be submitted to legal@flaer.app.

**9.9 Response Time**

Flaer responds to all verified privacy requests within:

-   30 days (GDPR)

-   45 days (CCPA)

Extensions may apply when allowed by law.

**9.10 Verification Before Processing Requests**

To protect Users and Advertisers, Flaer may verify identity using:

-   email verification,

-   account confirmation,

-   Stripe payout verification (if applicable),

-   confirmation from the Instagram account owner.

Flaer will never delete financial records needed for regulatory
compliance.

**9.11 Deletion After Death or Inactivity**

If Flaer receives a valid legal request from an authorized
representative or executor, we will:

-   delete the account data,

-   stop all processing,

-   retain only legally required financial records.

Inactive accounts may be deleted after extended inactivity as permitted
by law.

**10. International Data Transfers**

Because Flaer operates globally and relies on third-party service
providers located outside your country of residence, your personal data
may be transferred to, stored in, or processed in countries other than
your own. These countries may have data protection laws that differ from
those in your jurisdiction. Whenever such transfers occur, Flaer ensures
they are protected by appropriate safeguards and contractual
protections.

**10.1 Primary Storage Location (United States)**

Flaer stores and processes all platform data---including User content,
insights, and account information---on Amazon Web Services (AWS) located
in:

-   United States (US East --- N. Virginia, us-east-1)

Data stored in AWS is protected by:

-   encryption at rest (AES-256),

-   encryption in transit (TLS 1.2+),

-   AWS compliance with SOC 2, ISO 27001, PCI DSS, and other
    international standards.

**10.2 Transfers to Service Providers Outside Your Country**

Flaer uses the following service providers that may process data in the
United States or other regions:

-   Meta / Instagram (U.S. and global)

-   Stripe (Payments) --- typically U.S.

-   Appsflyer (Attribution) --- global distributed network

-   AWS (Hosting) --- United States

-   Email delivery services --- typically U.S.

These providers process only the data necessary to deliver their
services and are contractually obligated to protect it. Flaer does not
allow third-party providers to use personal data for advertising or
independent profiling.

**10.3 Data Transfers for EEA/UK/Swiss Users (GDPR Compliance)**

If you are located in the European Economic Area (EEA), the United
Kingdom, or Switzerland, your personal data may be transferred to the
United States or other third countries that are not deemed to provide an
equivalent level of data protection. When these transfers occur, Flaer
relies on:

-   Standard Contractual Clauses (SCCs) approved by the European
    Commission,

-   UK IDTA Addendum (where applicable),

-   Meta/Stripe/Appsflyer legally approved transfer mechanisms,

-   Supplementary technical measures, such as encryption and strict
    access control.

These mechanisms ensure your data remains protected even when
transferred outside the EEA.

**10.4 User Consent for International Transfers**

By using the Flaer apps or providing information to us, you acknowledge
that your data may be transferred to and processed in:

-   the United States,

-   the European Union,

-   or other jurisdictions where our service providers operate.

If you do not agree to such transfers, you must discontinue using the
service.

**10.5 Transfers Required by Law**

Flaer may disclose or transfer data internationally when legally
required, including:

-   responding to lawful requests from courts or authorities,

-   fulfilling tax or financial reporting obligations,

-   complying with payment regulations (such as AML/KYC obligations
    enforced by Stripe).

Such transfers are limited to the minimum data necessary.

**10.6 Continued Protection After Transfer**

Regardless of location, Flaer ensures your personal data is protected
by:

-   encryption at rest and in transit,

-   restricted access to production systems,

-   contractual data protection agreements with all processors,

-   periodic review of third-party compliance.

All processing remains consistent with this Privacy Policy.

**11. Children's Privacy**

Flaer is not intended for children and does not knowingly collect
personal data from anyone under the age required to have an independent
Instagram account or to receive monetary payouts.

**11.1 Minimum Age Requirements**

To use the Flaer Customer App or Flaer Ads App, Users must meet all of
the following:

-   be eligible to maintain a valid Instagram account under Meta's
    minimum age requirement (typically 13, or older depending on
    country),

-   be legally permitted to enter into binding agreements in their
    jurisdiction,

-   be at least 18 years old to receive monetary payouts through Stripe
    or participate in reward programs.

If you do not meet these age requirements, you may not use Flaer.

**11.2 No Knowing Collection of Children's Data**

Flaer does not knowingly collect, store, or process any personal
information from children under:

-   13 years old (COPPA standard),

-   the age of digital consent in the EEA/UK (generally 13--16 depending
    on country).

If Flaer becomes aware that a User does not meet the age requirements,
we will:

-   immediately disable the account,

-   delete all personal data,

-   retain only records required for fraud prevention or legal
    compliance.

**11.3 Stripe Age Verification for Payouts**

Stripe may require Users to provide information to verify age and
eligibility for payouts. This verification is handled by Stripe and is
not visible to Flaer. If Stripe determines that a User does not meet
legal age requirements:

-   payouts will not be processed,

-   rewards may be forfeited,

-   the account may be disabled.

**11.4 Advertisers**

Businesses using the Flaer Ads App must be operated by individuals who
are:

-   at least 18 years old, and

-   authorized to manage a business profile.

We do not allow minors to create or manage Advertiser accounts.

**11.5 Reporting Concerns**

If you believe that a child's information has been collected by mistake,
contact us at:

-   legal@flaer.app

Flaer will investigate and delete any data collected from an ineligible
child.

**12. Changes to This Privacy Policy**

We may update or modify this Privacy Policy from time to time to reflect
changes in our products, services, legal obligations, or operational
practices. When we make changes, we will update the "Last Updated" date
at the top of this document.

If the changes are significant, we will provide additional notice
through one or more of the following methods:

-   posting an in-app notification,

-   sending an email to the address associated with your account,

-   displaying an announcement on our website.

All changes become effective when posted unless otherwise specified.
Your continued use of the Flaer Customer App or Flaer Ads App after the
revised Privacy Policy becomes effective constitutes your acceptance of
the updated terms. If you do not agree to the updated Privacy Policy,
you must stop using the service and may request account deletion at
legal@flaer.app.

**13. Contact Information**

If you have questions, requests, or concerns regarding this Privacy
Policy or our data practices, you may contact us at:

Flaer, Inc.

251 Little Falls Drive Wilmington, DE 19808 United States

Email: legal@flaer.app

We respond to verified privacy-related requests within the timeframes
required by applicable law.

**14. Effective Date and Scope**

This Privacy Policy applies to all Users and Advertisers who use the
Flaer Customer App, the Flaer Ads App, or any related services provided
by Flaer, Inc. It also applies to all personal data processed in
connection with these services, regardless of the User's country of
residence.

This Privacy Policy is effective as of:

-   December 1, 2025

and remains in effect until replaced or updated. Any future revisions
will be posted within the app or on our website and will include a new
"Last Updated" date. Your continued use of Flaer after the effective
date of an updated Privacy Policy constitutes acceptance of the revised
terms.
