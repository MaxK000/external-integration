# Protocol Integration

This repository contains metadata for integrating external protocols, including addresses and relevant integration URLs for various markets.

## Metadata Structure

The JSON file includes details for multiple objects (PT, YT, LP), each corresponding to different parts of the protocol with specific chain IDs, addresses, integration URLs, and descriptions.

### Fields

#### Protocols fields

 - name: The name of the protocol.
 - icon: The protocol’s logo.
 - metadata: This section contains detailed information about the protocol's integration assets.

#### Asset fields
 - chainId: chainId of the integrated assets
 - address: Market address of the integrated assets
 - integrationUrl: Link to the page that integrated the asset
 - description: Description of the asset

### Example

```json
{
  "name": "Protocol Name 2",
  "icon": "logo.jpeg",
  "metadata": {
    "pt": [
      {
        "chainId": 1,
        "address": "0x332a8ee60edff0a11cf3994b1b846bbc27d3dcd6",
        "integrationUrl": "https://www.pendle.magpiexyz.io/stake",
        "description": "hello it's pt"
      }
    ],
    "yt": [
      {
        "chainId": 1,
        "address": "0x1cae47aa3e10a77c55ee32f8623d6b5acc947344",
        "integrationUrl": "https://www.pendle.magpiexyz.io/stake",
        "description": "hello it's yt"
      }
    ],
    "lp": [
      {
        "chainId": 1,
        "address": "0xcae62858db831272a03768f5844cbe1b40bb381f",
        "integrationUrl": "https://www.pendle.magpiexyz.io/stake",
        "description": "hello it's lp"
      }
    ]
  }
}
```