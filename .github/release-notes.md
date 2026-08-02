## Version Changes

| Component | Previous | Current |
| --- | --- | --- |
| Release tag | ${PREVIOUS_VERSION} | ${RELEASE_VERSION} |
| Application version | ${PREVIOUS_VERSION} | ${RELEASE_VERSION} |
| Helm chart package | ${PREVIOUS_VERSION} | ${RELEASE_VERSION} |
| Helm chart appVersion | ${PREVIOUS_VERSION} | ${RELEASE_VERSION} |
| Helm default image tag | ${PREVIOUS_VERSION} | ${RELEASE_VERSION} |

## Helm Chart

- Asset: `${CHART_FILENAME}`
- SHA256: `${CHART_DIGEST_NAME}`
- Download: ${CHART_DOWNLOAD_URL}

This chart package is published directly from the repository, so `version`, `appVersion`, and `platform.image.tag` already match the release tag.

```bash
helm install ret2shell ${CHART_DOWNLOAD_URL} -n ret2shell-platform --create-namespace
```

## Web Distribution

- Asset: `${WEB_DIST_FILENAME}`
- SHA256: `${WEB_DIST_DIGEST_NAME}`

## Binaries

${BINARY_ROWS}
