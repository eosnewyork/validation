Snapshot only Run against 1.0.1

```
time validate_chain --url http://localhost:8888 --snapshot ./snapshot.csv --check-accounts --ignore-errors --num-threads 200 --out-file ./validation.txt  --currency-check "10000000000.0000 EOS" 2> ./errors.log
Resetting file ./validation.txt
Getting chain information
{u'block_cpu_limit': 199900,
 u'block_net_limit': 1048576,
 u'chain_id': u'67fc1919ce5f203b0ba1f315ad9059a04056b17b9ac056ccba7a5c8ebd98554a',
 u'head_block_id': u'0000168464e7a1735f558d39987b6a3d9223aec55a7f48fa55eefc4f5880c60b',
 u'head_block_num': 5764,
 u'head_block_producer': u'eosio',
 u'head_block_time': u'2018-06-03T03:35:15',
 u'last_irreversible_block_id': u'00001683ec83093915fb0827fed5df6f18b6844b3f3672d17d36705a2eddb8cf',
 u'last_irreversible_block_num': 5763,
 u'server_version': u'0961a560',
 u'virtual_block_cpu_limit': 3548864,
 u'virtual_block_net_limit': 334569829}

real    17m50.690s
user    20m17.829s
sys     10m35.342s
```
