# ERC20TOKENADDRESS API

## What is the ERC20TOKENADDRESS Api?

The ERC20TOKENADDRTESS Api is used to get all ERC20 tokens owned by an address.

<!-- How to call the enpiont  -->

<!-- Prerequisites -->

## Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [NPM](https://www.npmjs.com/get-npm) or [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
- [Moralis](https://docs.moralis.io/)

## How to use the Resolve ENS Name API

### Endpoint Url

```text
Get https://web3-express-api.vercel.app/v1/getERC20Tokens/address:
```

### Parameters

| Parameter Name | Description | Required | Type | Parameter Type |
| :--- | :--- | :--- | :--- | :--- |
| address | The ENS address to resolve | Yes | string | Path |
|x-api-key| The API key for the Moralis server | Yes | string | Header |

### Example Request Url

```text
https://web3-express-api.vercel.app/v1/getERC20Tokens/0xbc4ca0eda7647a8ab7c2061c2e118a18a936f13d
```

<!-- tabs -->

{% tabs %}

{% tab title="React.js" %}

{% endtab %}

{% tab title="vanilla.js"}

{% endtab %}

{% tab title="Angular"}

{% endtab %}

{% tab title="Vue.js"}

{% endtab %}

{% tab title="Curl" %}

{% endtab %}

{% endtab %}

## Example Response Body

```json
{
    "token_address": "0xefd6c64533602ac55ab64442307f6fe2c9307305",
    "name": "APE",
    "symbol": "APE",
    "logo": null,
    "thumbnail": null,
    "decimals": 18,
    "balance": "101715701444169451516503179"
  }
```

## Error Responses

| Error Code | Description |
| :--- | :--- |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |
| 500 | Internal Server Error |

