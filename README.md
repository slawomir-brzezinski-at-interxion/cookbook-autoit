# autoit-cookbook

Cookbook to install AutoIt. AutoIt helps to install those akward applications that require GUI install.

## Supported Platforms

Windows

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['autoit']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### autoit::default

Include `autoit` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[autoit::default]"
  ]
}
```

## License and Authors

Author:: Taliesin Sisson (<taliesins@yahoo.com>)
