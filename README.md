# sebagomez scoop bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/sebagomez/scoopbucket/actions/workflows/ci.yml/badge.svg)](https://github.com/sebagomez/scoopbucket/actions/workflows/ci.yml) [![Excavator](https://github.com/sebagomez/scoopbucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/sebagomez/scoopbucket/actions/workflows/excavator.yml)

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add sebagomez https://github.com/sebagomez/scoopbucket
scoop install sebagomez/<manifestname>
```

The source of these commands are in https://github.com/sebagomez/psutils