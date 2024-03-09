Challenge: I Hope You Have The Software

Flag: RWSC{!t5_a_t4c3r_f!l3_:D}

Method:

After downloading the packet tracer file, I searched for every services in all the servers, which look identical except server 6

![server](https://github.com/Cryogas/RENTAS-RAWSEC-FINAL-FRESH_HASHER/assets/136941894/7ac2e015-caad-40ab-8b23-3c4c5792b494)



I realized that it displays 0 on the window, when it was supposed to display 6, since it is the 6th server. There is nothing in the http service too.

![Screenshot 2024-03-09 154118](https://github.com/Cryogas/RENTAS-RAWSEC-FINAL-FRESH_HASHER/assets/136941894/2166292b-27ec-4cba-bc62-b08015bad2fb)



I then discovered the 6 is weirdly written, turns out it is 0 overlapping with 6.

![server-06](https://github.com/Cryogas/RENTAS-RAWSEC-FINAL-FRESH_HASHER/assets/136941894/28e5d873-58a0-4760-b0d2-0a26daa6e4c0)


After dragging away the server 0, server 6 appeared, and it has a webpage named index.html

![server 6](https://github.com/Cryogas/RENTAS-RAWSEC-FINAL-FRESH_HASHER/assets/136941894/e91d6d75-37aa-4720-94e1-6967740c0241)



![index](https://github.com/Cryogas/RENTAS-RAWSEC-FINAL-FRESH_HASHER/assets/136941894/8163ab87-bb7e-407c-9ae0-eab02dd28d70)


Using the LLA in PC1 browser, I accessed the text and found the flag! :D!

![lla](https://github.com/Cryogas/RENTAS-RAWSEC-FINAL-FRESH_HASHER/assets/136941894/be65d8b8-54a7-468d-a277-f33effaa024d)

![server-6-flag](https://github.com/Cryogas/RENTAS-RAWSEC-FINAL-FRESH_HASHER/assets/136941894/de10f6c2-2bf0-4a0c-a2bc-6370d91d4814)

