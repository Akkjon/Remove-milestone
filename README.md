# Remove-milestone
A Github action to remove a milestone by the milestone's name
[Code of conduct](CODE_OF_CONDUCT.md)

## Inputs
### `milestone_name`
**Required** The name of the milestone, to close.


## Outputs
None

## Example usage
```yaml
uses: Akkjon/Close-milestone@02aae3442fc59bb5c0d04a8d4dd1fc528a7572f8
env:
  GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
with:
  milestone_name: milestone1
```
