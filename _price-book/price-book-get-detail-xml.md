---
title: Details of Price Book Request
position: 7
description: Get details for a specific custom price book.
type: get
endpoint: https://chapi.cloudhealthtech.com/v1/price_books/:id/specification
right_code_blocks:
  - code_block: |-
      {
        "specification": <XML>
      }
    title: Response Body
    language: json
  - code_block: |-
      curl --request GET -H 'Content-Type: application/json'
      'https://chapi.cloudhealthtech.com/v1/price_books/<id>/specification?api_key=<your_api_key>'
    title: Sample Request
    language: bash
---
