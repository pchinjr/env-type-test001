<img src="https://static.begin.app/node-minimal/readme-banner.png" width="553">

## example arc-env
```
@testing
ENV_NUMBER 012345678901234567890
ENV_STRING zeroonetwothreefourfivesixseveneightninezero
ENV_MIXED  012345678901234567890letters
```

deployed to AWS - must set ENV with CLI - works as expected
deployed to begin - add env var to begin console  - works as expected
sandbox - add env var with `.arc-env` not showing numbers correctly