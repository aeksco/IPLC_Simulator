# IPLC_Simulator
IPLC Simulator for CSCI 2500

#### Team:
- Alexander Schwartzberg
- Nitesh Dagli
- Khalil Fleming
- Michelle Lehner

#### TODOs:

We must implement the following functions:
```c
void iplc_sim_LRU_replace_on_miss(int index, int tag){}
void iplc_sim_LRU_update_on_hit(int index, int assoc_entry){}
void iplc_sim_process_pipeline_lw(int dest_reg, int base_reg, unsigned int data_address){}
void iplc_sim_process_pipeline_sw(int src_reg, int base_reg, unsigned int data_address){}
void iplc_sim_process_pipeline_branch(int reg1, int reg2){}
void iplc_sim_process_pipeline_jump(char *instruction){}
void iplc_sim_process_pipeline_syscall(){}
void iplc_sim_process_pipeline_nop(){}
```

#### Notes:

- Branch Prediction (p. 321-324)