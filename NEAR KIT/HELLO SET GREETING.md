---
action: call
network: testnet
contractId: hello.sleet.testnet
methodName: set_greeting
args: '{ "greeting": "Hello, from NEAR-KIT OBSIDIAN!" }'
options:
---
try the NEAR KIT: CALL METHOD command


feel free to toggle the network or use a different contact address

greeting contract
- hello.sleet.near
- hello.sleet.testnet

methodName
- set_greeting

args
- "greeting": "Hello, from NEAR-KIT OBSIDIAN!" }

options
- { "gas": "3 Tgas" }


=====================
#### 12/11/2025, 8:06:35 PM
```json
{
  "final_execution_status": "EXECUTED_OPTIMISTIC",
  "status": {
    "SuccessValue": ""
  },
  "transaction": {
    "signer_id": "bot.sleet.testnet",
    "public_key": "ed25519:Gt9aiwEhCBZnaixDvWDdf4iZKS1CXPbD6sY5t9MwwPao",
    "nonce": 222813771000051,
    "receiver_id": "hello.sleet.testnet",
    "actions": [
      {
        "FunctionCall": {
          "method_name": "set_greeting",
          "args": "eyJncmVldGluZyI6IkhlbGxvLCBmcm9tIE5FQVItS0lUIE9CU0lESUFOISJ9",
          "gas": 3000000000000,
          "deposit": "0"
        }
      }
    ],
    "signature": "ed25519:4cEEK1wAQiN9rnNkmeBkzZgHja1nS9xfDGTDCYnwKuN1M1aCyuo15FgXhaxwpiNbUS94KN4eAeJ1ekorvtzYFHpU",
    "hash": "8poBwSrvGCH4pebXeJEKoivukzX1aDhdcazmiTesEmyA",
    "priority_fee": 0
  },
  "transaction_outcome": {
    "id": "8poBwSrvGCH4pebXeJEKoivukzX1aDhdcazmiTesEmyA",
    "outcome": {
      "logs": [],
      "receipt_ids": [
        "A1jWbH21SK9HKWvbuHqCjwUGpj7S9Usk8QXG5zqqxFyA"
      ],
      "gas_burnt": 310777471755,
      "tokens_burnt": "31077747175500000000",
      "executor_id": "bot.sleet.testnet",
      "status": {
        "SuccessReceiptId": "A1jWbH21SK9HKWvbuHqCjwUGpj7S9Usk8QXG5zqqxFyA"
      },
      "metadata": {
        "version": 1,
        "gas_profile": null
      }
    },
    "block_hash": "Hkrh1BdWpQF1cPfZGEwHN9SdyQcR9N3E8oDFVn6nz7Za",
    "proof": []
  },
  "receipts_outcome": [
    {
      "id": "A1jWbH21SK9HKWvbuHqCjwUGpj7S9Usk8QXG5zqqxFyA",
      "outcome": {
        "logs": [
          "Set new greeting: Hello, from NEAR-KIT OBSIDIAN! by account: bot.sleet.testnet"
        ],
        "receipt_ids": [
          "AUqMm7s4qTdcKJmaCZEd2DY4FEc3q3KXZzJ9n4NrRCDe"
        ],
        "gas_burnt": 1114749760106,
        "tokens_burnt": "111474976010600000000",
        "executor_id": "hello.sleet.testnet",
        "status": {
          "SuccessValue": ""
        },
        "metadata": {
          "version": 3,
          "gas_profile": [
            {
              "cost": "BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "2118144888"
            },
            {
              "cost": "CONTRACT_LOADING_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "35445963"
            },
            {
              "cost": "CONTRACT_LOADING_BYTES",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "15177147235"
            },
            {
              "cost": "LOG_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "3543313050"
            },
            {
              "cost": "LOG_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "1029505698"
            },
            {
              "cost": "READ_MEMORY_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "7829589600"
            },
            {
              "cost": "READ_MEMORY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "440954628"
            },
            {
              "cost": "READ_REGISTER_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "5034330372"
            },
            {
              "cost": "READ_REGISTER_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "6110844"
            },
            {
              "cost": "STORAGE_WRITE_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "64196736000"
            },
            {
              "cost": "STORAGE_WRITE_EVICTED_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "867167289"
            },
            {
              "cost": "STORAGE_WRITE_KEY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "563862936"
            },
            {
              "cost": "STORAGE_WRITE_VALUE_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "930556170"
            },
            {
              "cost": "TOUCHING_TRIE_NODE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "45600000000"
            },
            {
              "cost": "UTF8_DECODING_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "3111779061"
            },
            {
              "cost": "UTF8_DECODING_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "22743277362"
            },
            {
              "cost": "WASM_INSTRUCTION",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "38794590912"
            },
            {
              "cost": "WRITE_MEMORY_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "5607589722"
            },
            {
              "cost": "WRITE_MEMORY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "168873864"
            },
            {
              "cost": "WRITE_REGISTER_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "8596567458"
            },
            {
              "cost": "WRITE_REGISTER_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "167268816"
            }
          ]
        }
      },
      "block_hash": "5xb6hvUQ3TzqrPHNNcGh147WVFYZRSVQQkVQgKPrbFjN",
      "proof": []
    }
  ]
}
```
#### 12/11/2025, 8:08:52 PM
```json
{
  "final_execution_status": "EXECUTED_OPTIMISTIC",
  "status": {
    "SuccessValue": ""
  },
  "transaction": {
    "signer_id": "bot.sleet.testnet",
    "public_key": "ed25519:Gt9aiwEhCBZnaixDvWDdf4iZKS1CXPbD6sY5t9MwwPao",
    "nonce": 222813771000052,
    "receiver_id": "hello.sleet.testnet",
    "actions": [
      {
        "FunctionCall": {
          "method_name": "set_greeting",
          "args": "eyJncmVldGluZyI6IkhlbGxvLCBmcm9tIE5FQVItS0lUIE9CU0lESUFOISJ9",
          "gas": 3000000000000,
          "deposit": "0"
        }
      }
    ],
    "signature": "ed25519:3Yjp2hvTZ7iqbYh7WYGM6jZPpW1isMGH1ZNym1GKYUipm18Mq9hZkox3hhymBtVTMWeXJzpwp3tW8rryKMTAiuGa",
    "hash": "6HamxFPjzcorkYaWbg2DCXagjrBuFg8WwPQLz8nuWyhs",
    "priority_fee": 0
  },
  "transaction_outcome": {
    "id": "6HamxFPjzcorkYaWbg2DCXagjrBuFg8WwPQLz8nuWyhs",
    "outcome": {
      "logs": [],
      "receipt_ids": [
        "BZ97bjRjBRBwE5JaXRmVAmd2Yixgv8iHMQb93mXVwVN7"
      ],
      "gas_burnt": 310777471755,
      "tokens_burnt": "31077747175500000000",
      "executor_id": "bot.sleet.testnet",
      "status": {
        "SuccessReceiptId": "BZ97bjRjBRBwE5JaXRmVAmd2Yixgv8iHMQb93mXVwVN7"
      },
      "metadata": {
        "version": 1,
        "gas_profile": null
      }
    },
    "block_hash": "HKGdy99xd4mfjZv1fAMZsEKDh1DcXqAnMWqFK6BmBa2T",
    "proof": []
  },
  "receipts_outcome": [
    {
      "id": "BZ97bjRjBRBwE5JaXRmVAmd2Yixgv8iHMQb93mXVwVN7",
      "outcome": {
        "logs": [
          "Set new greeting: Hello, from NEAR-KIT OBSIDIAN! by account: bot.sleet.testnet"
        ],
        "receipt_ids": [
          "DK4EhB2MDaTpSdtPELSfdDQwJXdgyff8mfMkJqjqbG7t"
        ],
        "gas_burnt": 1114857516719,
        "tokens_burnt": "111485751671900000000",
        "executor_id": "hello.sleet.testnet",
        "status": {
          "SuccessValue": ""
        },
        "metadata": {
          "version": 3,
          "gas_profile": [
            {
              "cost": "BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "2118144888"
            },
            {
              "cost": "CONTRACT_LOADING_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "35445963"
            },
            {
              "cost": "CONTRACT_LOADING_BYTES",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "15177147235"
            },
            {
              "cost": "LOG_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "3543313050"
            },
            {
              "cost": "LOG_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "1029505698"
            },
            {
              "cost": "READ_MEMORY_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "7829589600"
            },
            {
              "cost": "READ_MEMORY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "440954628"
            },
            {
              "cost": "READ_REGISTER_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "5034330372"
            },
            {
              "cost": "READ_REGISTER_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "6110844"
            },
            {
              "cost": "STORAGE_WRITE_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "64196736000"
            },
            {
              "cost": "STORAGE_WRITE_EVICTED_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "963519210"
            },
            {
              "cost": "STORAGE_WRITE_KEY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "563862936"
            },
            {
              "cost": "STORAGE_WRITE_VALUE_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "930556170"
            },
            {
              "cost": "TOUCHING_TRIE_NODE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "45600000000"
            },
            {
              "cost": "UTF8_DECODING_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "3111779061"
            },
            {
              "cost": "UTF8_DECODING_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "22743277362"
            },
            {
              "cost": "WASM_INSTRUCTION",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "38794590912"
            },
            {
              "cost": "WRITE_MEMORY_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "5607589722"
            },
            {
              "cost": "WRITE_MEMORY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "168873864"
            },
            {
              "cost": "WRITE_REGISTER_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "8596567458"
            },
            {
              "cost": "WRITE_REGISTER_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "178673508"
            }
          ]
        }
      },
      "block_hash": "A4dTaBCoJohBqK3ewCxmWk4MfHWPvGUvzthEKKJy93vq",
      "proof": []
    }
  ]
}
```
#### 12/11/2025, 8:15:25 PM
```json
{
  "final_execution_status": "EXECUTED_OPTIMISTIC",
  "status": {
    "SuccessValue": ""
  },
  "transaction": {
    "signer_id": "bot.sleet.testnet",
    "public_key": "ed25519:Gt9aiwEhCBZnaixDvWDdf4iZKS1CXPbD6sY5t9MwwPao",
    "nonce": 222813771000053,
    "receiver_id": "hello.sleet.testnet",
    "actions": [
      {
        "FunctionCall": {
          "method_name": "set_greeting",
          "args": "eyJncmVldGluZyI6IkhlbGxvLCBmcm9tIE5FQVItS0lUIE9CU0lESUFOISJ9",
          "gas": 30000000000000,
          "deposit": "0"
        }
      }
    ],
    "signature": "ed25519:4FKbWvqWq1jWd5wNv2zpRu9WBoR6eReqqYzvnYbEhDBpKwknfozDMmFK8SJmMtNcDTVH8fx1e67XDw2LNog6mkFz",
    "hash": "A1WP44FgpdKPCUTremGiC2Kv1Qeqe9gr6qv6A6PDw7G7",
    "priority_fee": 0
  },
  "transaction_outcome": {
    "id": "A1WP44FgpdKPCUTremGiC2Kv1Qeqe9gr6qv6A6PDw7G7",
    "outcome": {
      "logs": [],
      "receipt_ids": [
        "EjgDx7M378MkALH2v6CKN7VPiMdhkLcGHYU3caAUimNA"
      ],
      "gas_burnt": 310777471755,
      "tokens_burnt": "31077747175500000000",
      "executor_id": "bot.sleet.testnet",
      "status": {
        "SuccessReceiptId": "EjgDx7M378MkALH2v6CKN7VPiMdhkLcGHYU3caAUimNA"
      },
      "metadata": {
        "version": 1,
        "gas_profile": null
      }
    },
    "block_hash": "tAqQyjfLxZYvQzThJy2zdH7SxaHLe1EpBxR5XLZ9ruN",
    "proof": []
  },
  "receipts_outcome": [
    {
      "id": "EjgDx7M378MkALH2v6CKN7VPiMdhkLcGHYU3caAUimNA",
      "outcome": {
        "logs": [
          "Set new greeting: Hello, from NEAR-KIT OBSIDIAN! by account: bot.sleet.testnet"
        ],
        "receipt_ids": [
          "5VA7yJ4zHsvoGHBAxCjaWMHKzaup1X1n4hcB8L8oCqUB"
        ],
        "gas_burnt": 1114857516719,
        "tokens_burnt": "111485751671900000000",
        "executor_id": "hello.sleet.testnet",
        "status": {
          "SuccessValue": ""
        },
        "metadata": {
          "version": 3,
          "gas_profile": [
            {
              "cost": "BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "2118144888"
            },
            {
              "cost": "CONTRACT_LOADING_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "35445963"
            },
            {
              "cost": "CONTRACT_LOADING_BYTES",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "15177147235"
            },
            {
              "cost": "LOG_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "3543313050"
            },
            {
              "cost": "LOG_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "1029505698"
            },
            {
              "cost": "READ_MEMORY_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "7829589600"
            },
            {
              "cost": "READ_MEMORY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "440954628"
            },
            {
              "cost": "READ_REGISTER_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "5034330372"
            },
            {
              "cost": "READ_REGISTER_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "6110844"
            },
            {
              "cost": "STORAGE_WRITE_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "64196736000"
            },
            {
              "cost": "STORAGE_WRITE_EVICTED_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "963519210"
            },
            {
              "cost": "STORAGE_WRITE_KEY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "563862936"
            },
            {
              "cost": "STORAGE_WRITE_VALUE_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "930556170"
            },
            {
              "cost": "TOUCHING_TRIE_NODE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "45600000000"
            },
            {
              "cost": "UTF8_DECODING_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "3111779061"
            },
            {
              "cost": "UTF8_DECODING_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "22743277362"
            },
            {
              "cost": "WASM_INSTRUCTION",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "38794590912"
            },
            {
              "cost": "WRITE_MEMORY_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "5607589722"
            },
            {
              "cost": "WRITE_MEMORY_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "168873864"
            },
            {
              "cost": "WRITE_REGISTER_BASE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "8596567458"
            },
            {
              "cost": "WRITE_REGISTER_BYTE",
              "cost_category": "WASM_HOST_COST",
              "gas_used": "178673508"
            }
          ]
        }
      },
      "block_hash": "ASPygbeQS6yZGKHeeCEb87xa3UytTtiF6vBUnRLXpq4t",
      "proof": []
    }
  ]
}
```