# Logical Time vs Real Time
- Logical Time embeds event time orderning relation
- Real Time is physical clock time


# Characteristics of Real Time Systems
- Deadline association with tasks
- Change is notion of correctness : If a task is completed after the completion of deadline, it will be considered as incorrect.

## Safe System
- A component which if fails do not damage other components.

## Reliable System
- That can operate for long durations without any failure.

- In real time systems, each system need to be reliable as failure of any system can damage other systems.

- Deadlines can be hard or soft.

- Fairness vs Real Time : RTS should meet deadlines even at overload conditions contrast to fairness in non real time systems.

# Traditional Systems
- Safety and Reliability can be independent in these systems. 

# Fail Safe state
- When fails do not damage other systems.
- Fail Safe State of Document Processing Program : Key values are saved in disk.

- Fail Safe states are used to make unreliable and unsafe systems safe. 

- In many real time systems, there are no **Fail Safe States**. In such systems, safety can ensured by increased reliability.


So how to make systems which do not fail?
- Making a component more reliable by following techniques : 
-> Checkpointing and rollback recovery.



# Types of Real Time Systems 

