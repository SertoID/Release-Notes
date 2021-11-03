# Serto Search API Notes

# [1.0.0](https://github.com/SertoID/serto-search-backend/compare/...v1.0.0) (2021-11-02)


### Bug Fixes

* Add migration for org profile ([9a50345](https://github.com/SertoID/serto-search-backend/commit/9a503451898ab1dbf393e86bb1d14709c834fd4c))
* Attempt to fix migrations ([3399015](https://github.com/SertoID/serto-search-backend/commit/3399015aa7394b20d39916b6a248f216189ea9f7))
* Check for deleted rows when inner joining search results ([9332e36](https://github.com/SertoID/serto-search-backend/commit/9332e3629b94e8507e5b05d7b738e868e916c5b3))
* DID config pugin upgrade ([6993a8a](https://github.com/SertoID/serto-search-backend/commit/6993a8a3a9124352f2b30d8fae03cb2dc75ac021))
* don't use case sensitivity when searching for did:ethr listings ([41ab3de](https://github.com/SertoID/serto-search-backend/commit/41ab3debe71135cf32ca2ff3e7f8c5bda293715a))
* Fix Org Profile test ([a63a9c0](https://github.com/SertoID/serto-search-backend/commit/a63a9c0b00da2538a03c1b46329916c640a5d220))
* Fix schema validation ([40254ee](https://github.com/SertoID/serto-search-backend/commit/40254ee4bd6f8747d6e5ce63030c49924a6fa614))
* Fix test ([83481bc](https://github.com/SertoID/serto-search-backend/commit/83481bc37984ea58513cebe534450ffa3a07c1fb))
* Fixing some tests ([71b1208](https://github.com/SertoID/serto-search-backend/commit/71b12089897551018aa711d7b68c717550b5dd0e))
* Manually add typeorm_metadata table ([510f21b](https://github.com/SertoID/serto-search-backend/commit/510f21b5de8cceee27f66566155bffcc276185d4))
* Manually modify migrations ([4bb482c](https://github.com/SertoID/serto-search-backend/commit/4bb482ca504f16abfb955822e2c50d1602c6d291))
* Small fixes to support beta clone ([507b41c](https://github.com/SertoID/serto-search-backend/commit/507b41cc61c1e70afffa3c041c4344af6d7a623c))
* Temporarily remove NFT test ([39b2006](https://github.com/SertoID/serto-search-backend/commit/39b2006d9a44fdcea7d5b414d25539c33d4ef390))
* Testing org profile VC with agent.serto.id ([146f8e0](https://github.com/SertoID/serto-search-backend/commit/146f8e0111f48ab7c97cd05fef0bd332ad9b15ea))
* Update test VC ([51ee5b0](https://github.com/SertoID/serto-search-backend/commit/51ee5b0a780c991fdbd06467b1b1f9c2a87b9d35))
* Update tests for new beta agent instance ([897cd0d](https://github.com/SertoID/serto-search-backend/commit/897cd0d11668f7e6c7102e8d4f90d91d468c8340))
* use checksummed address when searching for didListing ([448e930](https://github.com/SertoID/serto-search-backend/commit/448e9306e443d896630787e0563aee3c0516221f))
* Use org profile schema prefix instead of full path ([6b1a294](https://github.com/SertoID/serto-search-backend/commit/6b1a2940e7e6f9cc2b5e9a042629ae0f840aa371))
* Using verify.serto.id to test did:ethr in DID configuration ([344fbc1](https://github.com/SertoID/serto-search-backend/commit/344fbc13c56b32f0e727d8c012101999154627bb))


### Features

* Add DIDComm endpoint ([5495cdb](https://github.com/SertoID/serto-search-backend/commit/5495cdb32227407aa93ffa87c6bd4b790209bc05))
* Add DIDComm endpoint to didDocEntry ([b9ccaba](https://github.com/SertoID/serto-search-backend/commit/b9ccaba8b7b88ffd1a1d877d0209a85ea5428e46))
* Add endpoint to get current org profile schema, string_agg update ([2c800e3](https://github.com/SertoID/serto-search-backend/commit/2c800e3d02027c21995cd322b7398f97e066b25c))
* add ethService which provides utility for ethereum features ([489854f](https://github.com/SertoID/serto-search-backend/commit/489854fec9ca5a61c8d322450ded8e6e20b1e984))
* Add pagination to search ([80c85a9](https://github.com/SertoID/serto-search-backend/commit/80c85a90fea32527056390a86bd78bd3da9f600f))
* Add process-vc route ([48eed6f](https://github.com/SertoID/serto-search-backend/commit/48eed6f38444b239c19fda9d1a30c79770953269))
* Add vcService ([4befccc](https://github.com/SertoID/serto-search-backend/commit/4befccc3511a11e748fcb87ad8cce24ad8b4682c))
* Attempt to add array of didDocs to ListingSummary ([6696798](https://github.com/SertoID/serto-search-backend/commit/6696798652e7706b1ee1f5ccdadbb5bca2ccb162))
* Create view entity for search purposes, refactor search queries ([278ba08](https://github.com/SertoID/serto-search-backend/commit/278ba08b2c460ad708f413a72a0bbc0c544f2c34))
* Registry endpoint ([03b7f1c](https://github.com/SertoID/serto-search-backend/commit/03b7f1c7d98e9f0b39d272d6796a4b31e6e33fd9))
* Return all didDocs in ListingSummary ([eb4293b](https://github.com/SertoID/serto-search-backend/commit/eb4293b7f6732a0aa3b2be8fcd3d910342f522d2))
* Update queries to get domain listings with name and description, if available ([3fee72f](https://github.com/SertoID/serto-search-backend/commit/3fee72f6c9df44f1fd27918ed040c046cf45d4a3))

# 1.0.0 (2021-10-20)

### Bug Fixes

- Add migration for org profile ([9a50345](https://github.com/SertoID/serto-search-backend/commit/9a503451898ab1dbf393e86bb1d14709c834fd4c))
- Attempt to fix migrations ([3399015](https://github.com/SertoID/serto-search-backend/commit/3399015aa7394b20d39916b6a248f216189ea9f7))
- Check for deleted rows when inner joining search results ([9332e36](https://github.com/SertoID/serto-search-backend/commit/9332e3629b94e8507e5b05d7b738e868e916c5b3))
- DID config pugin upgrade ([6993a8a](https://github.com/SertoID/serto-search-backend/commit/6993a8a3a9124352f2b30d8fae03cb2dc75ac021))
- don't use case sensitivity when searching for did:ethr listings ([41ab3de](https://github.com/SertoID/serto-search-backend/commit/41ab3debe71135cf32ca2ff3e7f8c5bda293715a))
- Fix Org Profile test ([a63a9c0](https://github.com/SertoID/serto-search-backend/commit/a63a9c0b00da2538a03c1b46329916c640a5d220))
- Fix schema validation ([40254ee](https://github.com/SertoID/serto-search-backend/commit/40254ee4bd6f8747d6e5ce63030c49924a6fa614))
- Fix test ([83481bc](https://github.com/SertoID/serto-search-backend/commit/83481bc37984ea58513cebe534450ffa3a07c1fb))
- Fixing some tests ([71b1208](https://github.com/SertoID/serto-search-backend/commit/71b12089897551018aa711d7b68c717550b5dd0e))
- Manually add typeorm_metadata table ([510f21b](https://github.com/SertoID/serto-search-backend/commit/510f21b5de8cceee27f66566155bffcc276185d4))
- Manually modify migrations ([4bb482c](https://github.com/SertoID/serto-search-backend/commit/4bb482ca504f16abfb955822e2c50d1602c6d291))
- Small fixes to support beta clone ([507b41c](https://github.com/SertoID/serto-search-backend/commit/507b41cc61c1e70afffa3c041c4344af6d7a623c))
- Temporarily remove NFT test ([39b2006](https://github.com/SertoID/serto-search-backend/commit/39b2006d9a44fdcea7d5b414d25539c33d4ef390))
- Testing org profile VC with agent.serto.id ([146f8e0](https://github.com/SertoID/serto-search-backend/commit/146f8e0111f48ab7c97cd05fef0bd332ad9b15ea))
- Update test VC ([51ee5b0](https://github.com/SertoID/serto-search-backend/commit/51ee5b0a780c991fdbd06467b1b1f9c2a87b9d35))
- Update tests for new beta agent instance ([897cd0d](https://github.com/SertoID/serto-search-backend/commit/897cd0d11668f7e6c7102e8d4f90d91d468c8340))
- use checksummed address when searching for didListing ([448e930](https://github.com/SertoID/serto-search-backend/commit/448e9306e443d896630787e0563aee3c0516221f))
- Use org profile schema prefix instead of full path ([6b1a294](https://github.com/SertoID/serto-search-backend/commit/6b1a2940e7e6f9cc2b5e9a042629ae0f840aa371))
- Using verify.serto.id to test did:ethr in DID configuration ([344fbc1](https://github.com/SertoID/serto-search-backend/commit/344fbc13c56b32f0e727d8c012101999154627bb))

### Features

- Add DIDComm endpoint ([5495cdb](https://github.com/SertoID/serto-search-backend/commit/5495cdb32227407aa93ffa87c6bd4b790209bc05))
- Add DIDComm endpoint to didDocEntry ([b9ccaba](https://github.com/SertoID/serto-search-backend/commit/b9ccaba8b7b88ffd1a1d877d0209a85ea5428e46))
- Add endpoint to get current org profile schema, string_agg update ([2c800e3](https://github.com/SertoID/serto-search-backend/commit/2c800e3d02027c21995cd322b7398f97e066b25c))
- add ethService which provides utility for ethereum features ([489854f](https://github.com/SertoID/serto-search-backend/commit/489854fec9ca5a61c8d322450ded8e6e20b1e984))
- Add pagination to search ([80c85a9](https://github.com/SertoID/serto-search-backend/commit/80c85a90fea32527056390a86bd78bd3da9f600f))
- Add process-vc route ([48eed6f](https://github.com/SertoID/serto-search-backend/commit/48eed6f38444b239c19fda9d1a30c79770953269))
- Add vcService ([4befccc](https://github.com/SertoID/serto-search-backend/commit/4befccc3511a11e748fcb87ad8cce24ad8b4682c))
- Attempt to add array of didDocs to ListingSummary ([6696798](https://github.com/SertoID/serto-search-backend/commit/6696798652e7706b1ee1f5ccdadbb5bca2ccb162))
- Create view entity for search purposes, refactor search queries ([278ba08](https://github.com/SertoID/serto-search-backend/commit/278ba08b2c460ad708f413a72a0bbc0c544f2c34))
- Registry endpoint ([03b7f1c](https://github.com/SertoID/serto-search-backend/commit/03b7f1c7d98e9f0b39d272d6796a4b31e6e33fd9))
- Return all didDocs in ListingSummary ([eb4293b](https://github.com/SertoID/serto-search-backend/commit/eb4293b7f6732a0aa3b2be8fcd3d910342f522d2))
- Update queries to get domain listings with name and description, if available ([3fee72f](https://github.com/SertoID/serto-search-backend/commit/3fee72f6c9df44f1fd27918ed040c046cf45d4a3))
