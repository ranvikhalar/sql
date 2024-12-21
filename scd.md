# **Scenerio 1 - TYPE 1 SCD**

If there is any change in the address, Type 1 SCD overwrites the change in the same row. It doesn't retain the old address/history. 

# **Scenerio 2 - Type 2 SCD**

If there is any change in the address, Type 2 SCD adds a new row for the new address and retains the old address in place as original. There is a unique Surrogate id/Primary Key assigned to each row for the reference. 