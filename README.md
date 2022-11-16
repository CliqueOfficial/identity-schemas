# identity-schemas

In order to reuse claims across different services is necessary to keep consistent data formatting. A Claim Schema encodes the structure of a particular claim by defining the usage of data slots.

Iden3 claims store data inside four data slots: two index slots(i_2,i_3) and two value slots (v_2, v_3). To properly design and fill a claim with information, it is necessary to define which data should be stored inside which data slots. These rules are encoded inside the Claim Schema.

Schemas are described via JSON-LD documents.
