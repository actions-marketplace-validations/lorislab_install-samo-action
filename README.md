## Example usage

```
- uses: lorislab/install-samo-action@v1
- run: samo project version
```

```
  - uses: lorislab/install-samo-action@v1
  - id: version
    run: echo "stdout=$(samo project version)" >> $GITHUB_OUTPUT
  - run: echo "${{ steps.version.outputs.stdout }}"
```

```
- uses: lorislab/install-samo-action@v1
  with:
    version: "3.3.0"
- run: samo project version    
```

## Development

#### Local development

Install the dependencies

```bash
npm install
```

#### Package for distribution

Run prepare

```bash
npm run prepare
```
