---
swagger: "2.0"
x-collection-name: Lisk
x-complete: 0
info:
  title: Lisk Requests peers data
  description: Search for specified peers.
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /transactions:
    get:
      summary: Requests transactions data
      description: Search for a specified transaction in the system.
      operationId: getTransactions
      x-api-path-slug: transactions-get
      parameters:
      - in: query
        name: blockId
        description: Block id to query
      - in: query
        name: fromTimestamp
        description: Starting unix timestamp
      - in: query
        name: height
        description: Current height of the network
      - in: query
        name: id
        description: Transaction id to query
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: maxAmount
        description: Maximum transaction amount in Beddows
      - in: query
        name: minAmount
        description: Minimum transaction amount in Beddows
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: recipientId
        description: Recipient lisk address
      - in: query
        name: recipientPublicKey
        description: Recipient public key
      - in: query
        name: senderId
        description: Sender lisk address
      - in: query
        name: senderIdOrRecipientId
        description: Lisk address
      - in: query
        name: senderPublicKey
        description: Sender public key
      - in: query
        name: sort
        description: Fields to sort results by
      - in: query
        name: toTimestamp
        description: Ending unix timestamp
      - in: query
        name: type
        description: Transaction type (0-7)
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Transactions
      - Data
  /blocks:
    get:
      summary: Requests blocks data
      description: Search for a specified block in the system.
      operationId: getBlocks
      x-api-path-slug: blocks-get
      parameters:
      - in: query
        name: blockId
        description: Block id to query
      - in: query
        name: generatorPublicKey
        description: Public key of the forger of the block
      - in: query
        name: height
        description: Current height of the network
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: sort
        description: Fields to sort results by
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Blocks
      - Data
  /delegates/forgers:
    get:
      summary: Requests next forgers data
      description: Returns a list of the next forgers in this delegate round.
      operationId: getForgers
      x-api-path-slug: delegatesforgers-get
      parameters:
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: offset
        description: Offset value for results
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Next
      - Forgers
      - Data
  /delegates:
    get:
      summary: Requests delegates data
      description: Search for a specified delegate in the system.
      operationId: getDelegates
      x-api-path-slug: delegates-get
      parameters:
      - in: query
        name: address
        description: Address of an account
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: publicKey
        description: Public key to query
      - in: query
        name: search
        description: Fuzzy delegate username to query
      - in: query
        name: secondPublicKey
        description: Second public key to query
      - in: query
        name: sort
        description: Fields to sort results by
      - in: query
        name: username
        description: Delegate username to query
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Delegates
      - Data
  /node/transactions/{state}:
    get:
      summary: Requests unprocessed transactions data
      description: |-
        By specifying the state of the transactions, you get a list of unprocessed transactions matching this state.
        Search for specific transactions by providing the appropriate parameters.
        If you post a batch of transactions, they will appear in the unprocessed list after a small delay, depending on server load.
      operationId: getPooledTransactions
      x-api-path-slug: nodetransactionsstate-get
      parameters:
      - in: query
        name: id
        description: Transaction id to query
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: recipientId
        description: Recipient lisk address
      - in: query
        name: recipientPublicKey
        description: Recipient public key
      - in: query
        name: senderId
        description: Sender lisk address
      - in: query
        name: senderPublicKey
        description: Sender public key
      - in: query
        name: sort
        description: Fields to sort results by
      - in: path
        name: state
        description: State of transactions to query
      - in: query
        name: type
        description: Transaction type (0-7)
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Unprocessed
      - Transactions
      - Data
  /node/status:
    get:
      summary: Requests status data
      description: Returns all current status data of the node, e.g. height and broadhash.
      operationId: getStatus
      x-api-path-slug: nodestatus-get
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Status
      - Data
  /node/constants:
    get:
      summary: Requests constants data
      description: Returns all current constants data on the system, e.g. Lisk epoch
        time and version.
      operationId: getConstants
      x-api-path-slug: nodeconstants-get
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Constants
      - Data
  /peers:
    get:
      summary: Requests peers data
      description: Search for specified peers.
      operationId: getPeers
      x-api-path-slug: peers-get
      parameters:
      - in: query
        name: broadhash
        description: Broadhash of the network
      - in: query
        name: height
        description: Current height of the network
      - in: query
        name: httpPort
        description: Http port of the node or delegate
      - in: query
        name: ip
        description: IP of the node or delegate
      - in: query
        name: limit
        description: Limit applied to results
      - in: query
        name: offset
        description: Offset value for results
      - in: query
        name: os
        description: OS of the node
      - in: query
        name: sort
        description: Fields to sort results by
      - in: query
        name: state
        description: Current state of the network
      - in: query
        name: version
        description: Lisk version of the node
      - in: query
        name: wsPort
        description: Web socket port for the node or delegate
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Peers
      - Data
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---