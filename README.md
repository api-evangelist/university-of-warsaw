# University of Warsaw

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Warsaw (Uniwersytet Warszawski) is Poland's largest and highest-ranked university and a member of the 4EU+ European University Alliance. Unusually for this cohort it operates real first-party programmable surfaces rather than only vendor tenancies: the USOS API at usosapps.uw.edu.pl, a documented OAuth 1.0a REST-like protocol over the institution's own academic database (courses, faculties, calendar, users, payments), and two springdoc services that publish their own OpenAPI and Swagger UI — the Student Portal 4EU+ API at api.sp4eu.uw.edu.pl (OpenAPI 3.1, 74 paths, read endpoints answer anonymously) and Jaskier at api.jaskier.uw.edu.pl, the university's central institutional API (OpenAPI 3.0.1, 729 paths, 458 schemas, bearer-gated data). Research data is handled by two institution-hosted repositories — Dane Badawcze UW (Dataverse, DOI prefix 10.58132) and ReIn UW (DSpace-CRIS 8.1) — each with a native REST API and an OAI-PMH 2.0 endpoint. The university runs its own Shibboleth SAML identity provider at login.uw.edu.pl, registered in eduGAIN through the Polish PIONIER.Id federation, and it is a DataCite repository client and a Crossref member with 31 DOI prefixes. What it does NOT have is a single central developer portal: the USOS developers site is the only signup surface, the library discovery layer is an Ex Libris Alma/Primo tenancy, and the LMS is a Moodle install with no public LTI advertisement.

**Areas:** Education · Higher Education · University · Poland · Europe · 4EU+ Alliance · Academic Data · Course Catalog · Research Data · Research Repository · Identity Federation · Library

## University of Warsaw on APIs.io

Everything profiled for University of Warsaw is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-warsaw/](https://apis.io/providers/university-of-warsaw/)** — or go straight to one of the APIs or properties below.

### APIs (152)

- [Dane Badawcze UW Research Data Repository REST API](https://apis.io/apis/university-of-warsaw/rdr-rest/) — The University of Warsaw Research Data Repository (Dane Badawcze UW) is a Dataverse-based institutional repository for long-term storage and open sharing of…
- [Dane Badawcze UW OAI-PMH Endpoint](https://apis.io/apis/university-of-warsaw/rdr-oai-pmh/) — OAI-PMH 2.0 metadata harvesting endpoint for the University of Warsaw Research Data Repository (Dataverse). The repository identifies itself as the "Dane…
- [University of Warsaw Apiref API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-apiref-api/) — Machine-readable method reference
- [University of Warsaw Apisrv API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-apisrv-api/) — USOS API server information and time
- [University of Warsaw Calendar API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-calendar-api/) — Academic calendar events
- [University of Warsaw Courses API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-courses-api/) — Courses and course editions
- [University of Warsaw Fac API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-fac-api/) — Faculties and organizational units
- [ReIn UW Institutional Repository REST API](https://apis.io/apis/university-of-warsaw/rein-uw-rest/) — The Institutional Repository of the University of Warsaw (ReIn UW, Repozytorium Instytucjonalne Uniwersytetu Warszawskiego) runs DSpace-CRIS 8.1…
- [ReIn UW OAI-PMH Endpoint](https://apis.io/apis/university-of-warsaw/rein-uw-oai-pmh/) — OAI-PMH 2.0 metadata harvesting endpoint for the Institutional Repository of the University of Warsaw. verb=Identify returns repositoryName "The…
- [University of Warsaw SAML Identity Provider (eduGAIN / PIONIER.Id)](https://apis.io/apis/university-of-warsaw/saml-idp/) — The university's own Shibboleth SAML 2.0 identity provider, entityID https://login.uw.edu.pl/idp, fronted by an Apereo CAS login at logowanie.uw.edu.pl. Its…
- [DataCite DOI Registration (REPOD / REPOD.DBUW)](https://apis.io/apis/university-of-warsaw/datacite-membership/) — The University of Warsaw registers DOIs through DataCite. Its DataCite provider is `repod` — "University of Warsaw – Interdisciplinary Centre for…
- [Crossref Membership (member 4211)](https://apis.io/apis/university-of-warsaw/crossref-membership/) — The University of Warsaw is Crossref member 4211, holding 31 DOI prefixes used across its journals and press imprints (10.7311, 10.14394, 10.7172, 10.55226,…
- [ROR Registration (039bjqg32)](https://apis.io/apis/university-of-warsaw/ror-registration/) — The Research Organization Registry record for the University of Warsaw, https://ror.org/039bjqg32, resolvable through the ROR API. It is the identifier the…
- [BUW Library Discovery (Ex Libris Alma / Primo, OMNIS)](https://apis.io/apis/university-of-warsaw/buw-primo/) — The University of Warsaw Library (BUW) migrated off NUKAT to Ex Libris Alma with Primo discovery in December 2024, joining the national OMNIS shared…
- [RepOD — Repository for Open Data (ICM UW)](https://apis.io/apis/university-of-warsaw/repod/) — RepOD is Poland's general-purpose repository for open research data, running the same Dataverse build (1.3.2) as Dane Badawcze UW and operated by the…
- [University of Warsaw Achievements Summary API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-achievementssummary-api/) — The AchievementsSummary API from University of Warsaw — 2 operation(s) for achievementssummary.
- [University of Warsaw Admin API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-admin-api/) — The Admin API from University of Warsaw — 9 operation(s) for admin.
- [University of Warsaw Analysis API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-analysis-api/) — The Analysis API from University of Warsaw — 2 operation(s) for analysis.
- [University of Warsaw API Key Principal API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-apikeyprincipal-api/) — The ApiKeyPrincipal API from University of Warsaw — 3 operation(s) for apikeyprincipal.
- [University of Warsaw Article API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-article-api/) — The Article API from University of Warsaw — 3 operation(s) for article.
- [University of Warsaw Article My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-articlemyuw-api/) — The ArticleMyUw API from University of Warsaw — 2 operation(s) for articlemyuw.
- [University of Warsaw Asset Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-assetmigration-api/) — The AssetMigration API from University of Warsaw — 4 operation(s) for assetmigration.
- [University of Warsaw Assets API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-assets-api/) — The Assets API from University of Warsaw — 5 operation(s) for assets.
- [University of Warsaw Building API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-building-api/) — The Building API from University of Warsaw — 25 operation(s) for building.
- [University of Warsaw Building Accessibility API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-buildingaccessibility-api/) — The BuildingAccessibility API from University of Warsaw — 13 operation(s) for buildingaccessibility.
- [University of Warsaw Building Attribute API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-buildingattribute-api/) — The BuildingAttribute API from University of Warsaw — 3 operation(s) for buildingattribute.
- [University of Warsaw Building Bon API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-buildingbon-api/) — The BuildingBon API from University of Warsaw — 7 operation(s) for buildingbon.
- [University of Warsaw Building Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-buildingmigration-api/) — The BuildingMigration API from University of Warsaw — 5 operation(s) for buildingmigration.
- [University of Warsaw Building My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-buildingmyuw-api/) — The BuildingMyUw API from University of Warsaw — 10 operation(s) for buildingmyuw.
- [University of Warsaw Building Ok Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-buildingokuw-api/) — The BuildingOkUw API from University of Warsaw — 11 operation(s) for buildingokuw.
- [University of Warsaw Business Entity API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-businessentity-api/) — The BusinessEntity API from University of Warsaw — 3 operation(s) for businessentity.
- [University of Warsaw Calculate Permissions API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-calculatepermissions-api/) — The CalculatePermissions API from University of Warsaw — 4 operation(s) for calculatepermissions.
- [University of Warsaw Campus API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-campus-api/) — The Campus API from University of Warsaw — 2 operation(s) for campus.
- [University of Warsaw Country API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-country-api/) — The Country API from University of Warsaw — 1 operation(s) for country.
- [University of Warsaw Course API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-course-api/) — The Course API from University of Warsaw — 27 operation(s) for course.
- [University of Warsaw Course Admin API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-courseadmin-api/) — The CourseAdmin API from University of Warsaw — 16 operation(s) for courseadmin.
- [University of Warsaw Course Areas Interests API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-courseareasinterests-api/) — The CourseAreasInterests API from University of Warsaw — 2 operation(s) for courseareasinterests.
- [University of Warsaw Course Certificate Admin API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-coursecertificateadmin-api/) — The CourseCertificateAdmin API from University of Warsaw — 10 operation(s) for coursecertificateadmin.
- [University of Warsaw Course Import Sp4eu/Export API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-courseimportsp4eu-export-api/) — The CourseImportSp4eu/Export API from University of Warsaw — 6 operation(s) for courseimportsp4eu/export.
- [University of Warsaw Course Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-coursemigration-api/) — The CourseMigration API from University of Warsaw — 7 operation(s) for coursemigration.
- [University of Warsaw Course My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-coursemyuw-api/) — The CourseMyUw API from University of Warsaw — 3 operation(s) for coursemyuw.
- [University of Warsaw Course Registration Info API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-courseregistrationinfo-api/) — The CourseRegistrationInfo API from University of Warsaw — 2 operation(s) for courseregistrationinfo.
- [University of Warsaw Course Sp4eu API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-coursesp4eu-api/) — The CourseSp4eu API from University of Warsaw — 14 operation(s) for coursesp4eu.
- [University of Warsaw Cpv Code API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-cpvcode-api/) — The CpvCode API from University of Warsaw — 6 operation(s) for cpvcode.
- [University of Warsaw Currency API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-currency-api/) — The Currency API from University of Warsaw — 2 operation(s) for currency.
- [University of Warsaw Event API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-event-api/) — The Event API from University of Warsaw — 16 operation(s) for event.
- [University of Warsaw FAQ API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-faq-api/) — The FAQ API from University of Warsaw — 2 operation(s) for faq.
- [University of Warsaw Framework Agreement API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-frameworkagreement-api/) — The FrameworkAgreement API from University of Warsaw — 20 operation(s) for frameworkagreement.
- [University of Warsaw Framework Agreement Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-frameworkagreementmigration-api/) — The FrameworkAgreementMigration API from University of Warsaw — 4 operation(s) for frameworkagreementmigration.
- [University of Warsaw Giveaway API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-giveaway-api/) — The Giveaway API from University of Warsaw — 7 operation(s) for giveaway.
- [University of Warsaw Giveaway My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-giveawaymyuw-api/) — The GiveawayMyUw API from University of Warsaw — 3 operation(s) for giveawaymyuw.
- [University of Warsaw History API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-history-api/) — The History API from University of Warsaw — 2 operation(s) for history.
- [University of Warsaw Home API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-home-api/) — The Home API from University of Warsaw — 3 operation(s) for home.
- [University of Warsaw Housing Option API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-housingoption-api/) — The HousingOption API from University of Warsaw — 6 operation(s) for housingoption.
- [University of Warsaw Housing Options API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-housingoptions-api/) — The HousingOptions API from University of Warsaw — 8 operation(s) for housingoptions.
- [University of Warsaw Housing Options Sp4eu API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-housingoptionssp4eu-api/) — The HousingOptionsSp4eu API from University of Warsaw — 6 operation(s) for housingoptionssp4eu.
- [University of Warsaw ID Card API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-idcard-api/) — The IdCard API from University of Warsaw — 4 operation(s) for idcard.
- [University of Warsaw ID Card My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-idcardmyuw-api/) — The IdCardMyUw API from University of Warsaw — 1 operation(s) for idcardmyuw.
- [University of Warsaw Idp Person API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-idpperson-api/) — The IdpPerson API from University of Warsaw — 3 operation(s) for idpperson.
- [University of Warsaw Item Used API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-itemused-api/) — The ItemUsed API from University of Warsaw — 9 operation(s) for itemused.
- [University of Warsaw Item Used My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-itemusedmyuw-api/) — The ItemUsedMyUw API from University of Warsaw — 4 operation(s) for itemusedmyuw.
- [University of Warsaw It Service API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-itservice-api/) — The ItService API from University of Warsaw — 8 operation(s) for itservice.
- [University of Warsaw It Service My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-itservicemyuw-api/) — The ItServiceMyUw API from University of Warsaw — 2 operation(s) for itservicemyuw.
- [University of Warsaw Keywords API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-keywords-api/) — The Keywords API from University of Warsaw — 4 operation(s) for keywords.
- [University of Warsaw Laboratory API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-laboratory-api/) — The Laboratory API from University of Warsaw — 12 operation(s) for laboratory.
- [University of Warsaw Laboratory Type API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-laboratorytype-api/) — The LaboratoryType API from University of Warsaw — 2 operation(s) for laboratorytype.
- [University of Warsaw Language API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-language-api/) — The Language API from University of Warsaw — 1 operation(s) for language.
- [University of Warsaw License API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-license-api/) — The License API from University of Warsaw — 6 operation(s) for license.
- [University of Warsaw License Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-licensemigration-api/) — The LicenseMigration API from University of Warsaw — 5 operation(s) for licensemigration.
- [University of Warsaw Magazine API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-magazine-api/) — The Magazine API from University of Warsaw — 2 operation(s) for magazine.
- [University of Warsaw Magazine Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-magazinemigration-api/) — The MagazineMigration API from University of Warsaw — 3 operation(s) for magazinemigration.
- [University of Warsaw Mobility Option API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-mobilityoption-api/) — The MobilityOption API from University of Warsaw — 5 operation(s) for mobilityoption.
- [University of Warsaw Mobility Option Admin API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-mobilityoptionadmin-api/) — The MobilityOptionAdmin API from University of Warsaw — 4 operation(s) for mobilityoptionadmin.
- [University of Warsaw Mobility Option Home API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-mobilityoptionhome-api/) — The MobilityOptionHome API from University of Warsaw — 3 operation(s) for mobilityoptionhome.
- [University of Warsaw Mobility Option Sp4eu API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-mobilityoptionsp4eu-api/) — The MobilityOptionSp4eu API from University of Warsaw — 4 operation(s) for mobilityoptionsp4eu.
- [University of Warsaw Monograph Publisher API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-monographpublisher-api/) — The MonographPublisher API from University of Warsaw — 2 operation(s) for monographpublisher.
- [University of Warsaw Monograph Publisher Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-monographpublishermigration-api/) — The MonographPublisherMigration API from University of Warsaw — 3 operation(s) for monographpublishermigration.
- [University of Warsaw Pass Control API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-passcontrol-api/) — The PassControl API from University of Warsaw — 5 operation(s) for passcontrol.
- [University of Warsaw Pass Control Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-passcontrolmigration-api/) — The PassControlMigration API from University of Warsaw — 5 operation(s) for passcontrolmigration.
- [University of Warsaw Pass Control My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-passcontrolmyuw-api/) — The PassControlMyUw API from University of Warsaw — 2 operation(s) for passcontrolmyuw.
- [University of Warsaw Patent API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-patent-api/) — The Patent API from University of Warsaw — 29 operation(s) for patent.
- [University of Warsaw Patent Public API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-patentpublic-api/) — The PatentPublic API from University of Warsaw — 1 operation(s) for patentpublic.
- [University of Warsaw Perm Department Cas Role API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-permdepartmentcasrole-api/) — The PermDepartmentCasRole API from University of Warsaw — 2 operation(s) for permdepartmentcasrole.
- [University of Warsaw Perm Department Person API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-permdepartmentperson-api/) — The PermDepartmentPerson API from University of Warsaw — 4 operation(s) for permdepartmentperson.
- [University of Warsaw Permissions API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-permissions-api/) — The Permissions API from University of Warsaw — 14 operation(s) for permissions.
- [University of Warsaw Perms Group API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-permsgroup-api/) — The PermsGroup API from University of Warsaw — 7 operation(s) for permsgroup.
- [University of Warsaw Person API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-person-api/) — The Person API from University of Warsaw — 3 operation(s) for person.
- [University of Warsaw Person Admin API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personadmin-api/) — The PersonAdmin API from University of Warsaw — 3 operation(s) for personadmin.
- [University of Warsaw Person Document API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-persondocument-api/) — The PersonDocument API from University of Warsaw — 3 operation(s) for persondocument.
- [University of Warsaw Person Principal API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personprincipal-api/) — The PersonPrincipal API from University of Warsaw — 8 operation(s) for personprincipal.
- [University of Warsaw Person Profile API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personprofile-api/) — The PersonProfile API from University of Warsaw — 4 operation(s) for personprofile.
- [University of Warsaw Person Role API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personrole-api/) — The PersonRole API from University of Warsaw — 4 operation(s) for personrole.
- [University of Warsaw Person System Role API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personsystemrole-api/) — The PersonSystemRole API from University of Warsaw — 10 operation(s) for personsystemrole.
- [University of Warsaw Person System Role Docsense API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personsystemroledocsense-api/) — The PersonSystemRoleDocsense API from University of Warsaw — 2 operation(s) for personsystemroledocsense.
- [University of Warsaw Person System Role Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personsystemrolemigration-api/) — The PersonSystemRoleMigration API from University of Warsaw — 5 operation(s) for personsystemrolemigration.
- [University of Warsaw Person System Role Sap API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-personsystemrolesap-api/) — The PersonSystemRoleSap API from University of Warsaw — 16 operation(s) for personsystemrolesap.
- [University of Warsaw Phone Number/Export API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-phonenumber-export-api/) — The PhoneNumber/Export API from University of Warsaw — 2 operation(s) for phonenumber/export.
- [University of Warsaw Principal API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-principal-api/) — The Principal API from University of Warsaw — 3 operation(s) for principal.
- [University of Warsaw Profile API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-profile-api/) — The Profile API from University of Warsaw — 32 operation(s) for profile.
- [University of Warsaw Profile Dspace API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-profiledspace-api/) — The ProfileDspace API from University of Warsaw — 3 operation(s) for profiledspace.
- [University of Warsaw Profile Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-profilemigration-api/) — The ProfileMigration API from University of Warsaw — 11 operation(s) for profilemigration.
- [University of Warsaw Profile My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-profilemyuw-api/) — The ProfileMyUw API from University of Warsaw — 7 operation(s) for profilemyuw.
- [University of Warsaw Profile Ok Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-profileokuw-api/) — The ProfileOkUw API from University of Warsaw — 11 operation(s) for profileokuw.
- [University of Warsaw Profile Person API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-profileperson-api/) — The ProfilePerson API from University of Warsaw — 4 operation(s) for profileperson.
- [University of Warsaw Project API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-project-api/) — The Project API from University of Warsaw — 26 operation(s) for project.
- [University of Warsaw Project Contract Type API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectcontracttype-api/) — The ProjectContractType API from University of Warsaw — 2 operation(s) for projectcontracttype.
- [University of Warsaw Project International Detail API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectinternationaldetail-api/) — The ProjectInternationalDetail API from University of Warsaw — 3 operation(s) for projectinternationaldetail.
- [University of Warsaw Project Member Role API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectmemberrole-api/) — The ProjectMemberRole API from University of Warsaw — 5 operation(s) for projectmemberrole.
- [University of Warsaw Project Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectmigration-api/) — The ProjectMigration API from University of Warsaw — 12 operation(s) for projectmigration.
- [University of Warsaw Project My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectmyuw-api/) — The ProjectMyUw API from University of Warsaw — 5 operation(s) for projectmyuw.
- [University of Warsaw Project Ok Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectokuw-api/) — The ProjectOkUw API from University of Warsaw — 3 operation(s) for projectokuw.
- [University of Warsaw Project Program API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectprogram-api/) — The ProjectProgram API from University of Warsaw — 3 operation(s) for projectprogram.
- [University of Warsaw Project Program Detailed API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectprogramdetailed-api/) — The ProjectProgramDetailed API from University of Warsaw — 3 operation(s) for projectprogramdetailed.
- [University of Warsaw Project Public API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectpublic-api/) — The ProjectPublic API from University of Warsaw — 1 operation(s) for projectpublic.
- [University of Warsaw Project Report API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-projectreport-api/) — The ProjectReport API from University of Warsaw — 6 operation(s) for projectreport.
- [University of Warsaw Psp Element API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-pspelement-api/) — The PspElement API from University of Warsaw — 2 operation(s) for pspelement.
- [University of Warsaw Publication API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-publication-api/) — The Publication API from University of Warsaw — 13 operation(s) for publication.
- [University of Warsaw Publication Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-publicationmigration-api/) — The PublicationMigration API from University of Warsaw — 4 operation(s) for publicationmigration.
- [University of Warsaw Publication My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-publicationmyuw-api/) — The PublicationMyUw API from University of Warsaw — 3 operation(s) for publicationmyuw.
- [University of Warsaw Public Procurement Legal Basis API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-publicprocurementlegalbasis-api/) — The PublicProcurementLegalBasis API from University of Warsaw — 2 operation(s) for publicprocurementlegalbasis.
- [University of Warsaw Public Procurement Plan API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-publicprocurementplan-api/) — The PublicProcurementPlan API from University of Warsaw — 7 operation(s) for publicprocurementplan.
- [University of Warsaw Public Procurement Plan Category API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-publicprocurementplancategory-api/) — The PublicProcurementPlanCategory API from University of Warsaw — 2 operation(s) for publicprocurementplancategory.
- [University of Warsaw Public Procurement Plan Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-publicprocurementplanmigration-api/) — The PublicProcurementPlanMigration API from University of Warsaw — 5 operation(s) for publicprocurementplanmigration.
- [University of Warsaw Registration Admin API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-registrationadmin-api/) — The RegistrationAdmin API from University of Warsaw — 3 operation(s) for registrationadmin.
- [University of Warsaw Research Set API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-researchset-api/) — The ResearchSet API from University of Warsaw — 7 operation(s) for researchset.
- [University of Warsaw Saml Metadata API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-samlmetadata-api/) — The SamlMetadata API from University of Warsaw — 2 operation(s) for samlmetadata.
- [University of Warsaw Sap Role API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-saprole-api/) — The SapRole API from University of Warsaw — 2 operation(s) for saprole.
- [University of Warsaw Science Field/Science Discipline API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-sciencefield-sciencediscipline-api/) — The ScienceField/ScienceDiscipline API from University of Warsaw — 6 operation(s) for sciencefield/sciencediscipline.
- [University of Warsaw Student Organization API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-studentorganization-api/) — The StudentOrganization API from University of Warsaw — 16 operation(s) for studentorganization.
- [University of Warsaw Student Organization My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-studentorganizationmyuw-api/) — The StudentOrganizationMyUw API from University of Warsaw — 2 operation(s) for studentorganizationmyuw.
- [University of Warsaw System API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-system-api/) — The System API from University of Warsaw — 2 operation(s) for system.
- [University of Warsaw System Rest API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-system-rest-api/) — The system-rest API from University of Warsaw — 2 operation(s) for system-rest.
- [University of Warsaw System Role API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-systemrole-api/) — The SystemRole API from University of Warsaw — 2 operation(s) for systemrole.
- [University of Warsaw Translation API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-translation-api/) — The Translation API from University of Warsaw — 3 operation(s) for translation.
- [University of Warsaw Translation Category API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-translationcategory-api/) — The TranslationCategory API from University of Warsaw — 2 operation(s) for translationcategory.
- [University of Warsaw Translation Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-translationmigration-api/) — The TranslationMigration API from University of Warsaw — 4 operation(s) for translationmigration.
- [University of Warsaw Tutorial API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-tutorial-api/) — The Tutorial API from University of Warsaw — 6 operation(s) for tutorial.
- [University of Warsaw Tutorial Admin API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-tutorialadmin-api/) — The TutorialAdmin API from University of Warsaw — 3 operation(s) for tutorialadmin.
- [University of Warsaw Tutorial Migration API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-tutorialmigration-api/) — The TutorialMigration API from University of Warsaw — 4 operation(s) for tutorialmigration.
- [University of Warsaw Tutorial Sp4eu API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-tutorialsp4eu-api/) — The TutorialSp4eu API from University of Warsaw — 4 operation(s) for tutorialsp4eu.
- [University of Warsaw Unit API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-unit-api/) — The Unit API from University of Warsaw — 8 operation(s) for unit.
- [University of Warsaw University Info API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-universityinfo-api/) — The UniversityInfo API from University of Warsaw — 3 operation(s) for universityinfo.
- [University of Warsaw User Preference API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-userpreference-api/) — The UserPreference API from University of Warsaw — 1 operation(s) for userpreference.
- [University of Warsaw Uw Economic Department API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-uweconomicdepartment-api/) — The UwEconomicDepartment API from University of Warsaw — 3 operation(s) for uweconomicdepartment.
- [University of Warsaw Uw Person API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-uwperson-api/) — The UwPerson API from University of Warsaw — 7 operation(s) for uwperson.
- [University of Warsaw Uw Person Docsense API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-uwpersondocsense-api/) — The UwPersonDocsense API from University of Warsaw — 3 operation(s) for uwpersondocsense.
- [University of Warsaw Uw Person My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-uwpersonmyuw-api/) — The UwPersonMyUw API from University of Warsaw — 1 operation(s) for uwpersonmyuw.
- [University of Warsaw Uw Unit API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-uwunit-api/) — The UwUnit API from University of Warsaw — 6 operation(s) for uwunit.
- [University of Warsaw Uw Unit My Uw API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-uwunitmyuw-api/) — The UwUnitMyUw API from University of Warsaw — 2 operation(s) for uwunitmyuw.
- [University of Warsaw API Key API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-api-key-api/) — The API Key API from University of Warsaw — 3 operation(s) for api key.
- [University of Warsaw Phone Number API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-phone-number-api/) — The Phone Number API from University of Warsaw — 7 operation(s) for phone number.
- [University of Warsaw Project Type API](https://apis.io/apis/university-of-warsaw/university-of-warsaw-project-type-api/) — The Project Type API from University of Warsaw — 3 operation(s) for project type.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of Warsaw Agentic Access](https://apis.io/agentic-access/university-of-warsaw/university-of-warsaw-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [USOS Course](https://apis.io/schemas/university-of-warsaw/university-of-warsaw-course/)
- [USOS Faculty](https://apis.io/schemas/university-of-warsaw/university-of-warsaw-faculty/)
- [USOS Installation](https://apis.io/schemas/university-of-warsaw/university-of-warsaw-installation/)
- [Student Portal 4EU+ Course](https://apis.io/schemas/university-of-warsaw/university-of-warsaw-sp4eu-course/)
- [Student Portal 4EU+ Tutorial](https://apis.io/schemas/university-of-warsaw/university-of-warsaw-sp4eu-tutorial/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [University Of Warsaw Course Structure](https://apis.io/json-structure/university-of-warsaw/university-of-warsaw-course-structure/)
- [University Of Warsaw Installation Structure](https://apis.io/json-structure/university-of-warsaw/university-of-warsaw-installation-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Warsaw Context](https://apis.io/jsonld/university-of-warsaw/university-of-warsaw-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Warsaw USOS API Vocabulary](https://apis.io/vocabularies/university-of-warsaw/university-of-warsaw-vocabulary/)

#### Examples (4)

Example requests and responses.

- [University Of Warsaw Course Error Example](https://apis.io/examples/university-of-warsaw/university-of-warsaw-course-error-example/)
- [University Of Warsaw Installation Example](https://apis.io/examples/university-of-warsaw/university-of-warsaw-installation-example/)
- [University Of Warsaw Now Example](https://apis.io/examples/university-of-warsaw/university-of-warsaw-now-example/)
- [University Of Warsaw Sp4Eu Tutorial Example](https://apis.io/examples/university-of-warsaw/university-of-warsaw-sp4eu-tutorial-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [USOS API (University of Warsaw) apiref API](https://apis.io/collections/university-of-warsaw/open-university-of-warsaw-apiref-api/)
- [USOS API (University of Warsaw) apiref apisrv API](https://apis.io/collections/university-of-warsaw/open-university-of-warsaw-apisrv-api/)
- [USOS API (University of Warsaw) apiref calendar API](https://apis.io/collections/university-of-warsaw/open-university-of-warsaw-calendar-api/)
- [USOS API (University of Warsaw) apiref courses API](https://apis.io/collections/university-of-warsaw/open-university-of-warsaw-courses-api/)
- [USOS API (University of Warsaw) apiref fac API](https://apis.io/collections/university-of-warsaw/open-university-of-warsaw-fac-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of Warsaw — jsonschema rules](https://apis.io/rules/university-of-warsaw/university-of-warsaw-jsonschema-spectral-rules/)
- [University of Warsaw API Rules](https://apis.io/rules/university-of-warsaw/university-of-warsaw-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Warsaw Authentication](https://apis.io/security/university-of-warsaw/university-of-warsaw-authentication/)
- [University Of Warsaw Domain Security](https://apis.io/security/university-of-warsaw/university-of-warsaw-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Warsaw Plans Pricing](https://apis.io/plans/university-of-warsaw/university-of-warsaw-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Warsaw Rate Limits](https://apis.io/rate-limits/university-of-warsaw/university-of-warsaw-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Warsaw Finops](https://apis.io/finops/university-of-warsaw/university-of-warsaw-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://en.uw.edu.pl/)
- [Documentation](https://usosapps.uw.edu.pl/developers/api/)
- [API reference](https://api.sp4eu.uw.edu.pl/)
- [Support](https://it.uw.edu.pl/pl/)
- [Blog](https://en.uw.edu.pl/category/news/feed/)
- [Privacy policy](https://www.uw.edu.pl/informacja-o-przetwarzaniu-danych-osobowych/)

## API Evangelist rating

**Kin Score 43.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 60.0 |
| Contract governance | 14.4 |
| Operational transparency | 10.5 |
| Developer ergonomics | 45.2 |
| Access clarity | 28.9 |

**Agent readiness 23.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly (partial credit) |

**Regulatory alignment 28.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-warsaw/](https://apis.io/providers/university-of-warsaw/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Warsaw: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-warsaw/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
