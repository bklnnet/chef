# reboot-now Cookbook

This cannot be any simpler, a startup cookbook to show basic concepts of chef.
It does what it says: reboots the box, that is it, just addit to your run list and voila...
Just do not forget to remove it from the list after the reboot, otherwise it will reboot on every client run, probably not what you want :-)

## Requirements

None, just basic chef environment, any version.

### Platforms

Whatever chef runs on

### Chef

- Chef 12.0 or later

### Cookbooks

- `toaster` - reboot-now needs toaster to brown your bagel.

## Attributes

None

### reboot-now::default

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['reboot-now']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### reboot-now::default

TODO: Write usage instructions for each cookbook.

e.g.
Just include `reboot-now` in your nodes `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[reboot-now]"
  ]
}
```

## Contributing

This is a public cookbook, your trade secrets are safe here :-)

## License and Authors

Authors: Your's Truly - mark@naumowicz.net

