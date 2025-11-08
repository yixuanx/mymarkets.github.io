# mymarkets.github.io

### TECH STACK:
- nodejs  [*python as math tooling]
  ---end to end delivery for projects, demonstration
  ---Money...
  
- java [=> go /cxx /rust] for core service, new gen young talents...

  - redis, api gateway...  [postgre]
  - kafka (*java), flink (*java)


  - ai: onnx pytorch; ai: image, llm ai gen agent rag (*help education for understanding as well)


# More:
UUID /Queue /API Gateway:

Redis uuid:
Scheme: Redis INC + Business Prefix	 
  - Applicable Scenarios: Order numbers, serial numbers (require readability)
  - Advantages: Ordered, readable, easy to implement
  - Disadvantages: Depends on Redis performance, long ID 

Scheme: Redis + Snowflake Algorithm Variant
  - Applicable Scenarios: High concurrency, no readability requirement (such as logs)
  - Advantages: High performance, compact ID, distributed friendly
  - Disadvantages: Unordered, depends on clock synchronization 


Apache Kafka
Kafka provides at least once semantics by default, but it can be configured to provide exactly once semantics. Deduplication in Kafka depends on:
• A unique message ID,
• And ensuring that consumers do not process the same offset repeatedly.


Flink: event based iteration with window and watermark, then for machine learning

---Nodejs [*python]: Projects delivery and demonstration,  for AI /math /exam as well.

Stocks & Money: The CEO of Southeast Asia's largest bank warns investors: "Fasten your seat belts, we are in for a bumpy ride."
