# mymarkets.github.io

### Tech stack:
- nodejs  (* and python as tooling for ai or math)
  - end to end delivery for projects, demonstration
  - money /math ...
  - ai: onnx pytorch; ai: image, llm ai gen agent rag (*help education for understanding as well)
  
- java [=> go /cxx /rust] for core service, new gen young talents...
    - Middle-wares: redis [postgre];  kafka (*java), flink (*java)...



# Middle-wares:
UUID /API Gateway /Queue:

- Redis: UUID /API Gateway:
    - Scheme: Redis INC atomic + Business Prefix	 
        - Applicable Scenarios: Order numbers, serial numbers (require readability)
        - Advantages: Ordered, readable, easy to implement
        - Disadvantages: Depends on Redis performance, long ID 

    - Scheme: Redis + Snowflake Algorithm Variant
        - Applicable Scenarios: High concurrency, no readability requirement (such as logs)
        - Advantages: High performance, compact ID, distributed friendly
        - Disadvantages: Unordered, depends on clock synchronization 


- Kafka: Exactly once for the queue:
    - Kafka provides at least once semantics by default, 
    - but it can be configured to provide exactly once semantics. Deduplication in Kafka depends on:
        - Unique message ID,
        - And ensuring that consumers do not process the same offset repeatedly.


- Flink: Event based iteration, with window and watermark, 
    - then for machine learning, onnx

- Nodejs ( * and python tooling ): 
    - for projects delivery and demonstration,  
    - for AI /math /exam as well.

- *Stocks /Money: The CEO of Southeast Asia's largest bank warns investors: "Fasten your seat belts, we are in for a bumpy ride."
