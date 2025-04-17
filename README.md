# Clamp based Power Monitoring circuit
#### Client Name: Trevor Schirmer

## Project Requirements
Core requirements are illustrated as below:
- The device should be able to use split core clamps to measure power usage in an electrical panel with below specifications:
    - 16 x 50/60 Amps measurements
    - 2 x ports for measuring 100/200 Amps circuits
    - 120V input supply or USB-C
- Reference project that can be a good starting point can be found at [this link](https://github.com/CircuitSetup/Expandable-6-Channel-ESP32-Energy-Meter/tree/master/Hardware).
- There should be an ability to add an external antenna if required such as [this](https://www.aliexpress.us/item/2251832583739183.html?spm=a2g0o.detail.pcDetailBottomMoreOtherSeller.3.405fKScpKScphm&gps-id=pcDetailBottomMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=9f926a67-102d-4b47-8fa1-02de5406b464&_t=gps-id:pcDetailBottomMoreOtherSeller,scm-url:1007.40050.354490.0,pvid:9f926a67-102d-4b47-8fa1-02de5406b464,tpp_buckets:668%232846%238110%231995&pdp_ext_f=%7B%22order%22%3A%2211%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%7D&pdp_npi=4%40dis%21USD%213.86%213.86%21%21%213.86%213.86%21%402103247417440837232415572e02f5%2110000015333196132%21rec%21US%21794602621%21XZ&utparam-url=scene%3ApcDetailBottomMoreOtherSeller%7Cquery_from%3A)
- End product should look something like in the image below with [this connector](https://www.aliexpress.us/item/2251832045396748.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.11.6cd17IOd7IOdzM&gps-id=pcDetailTopMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=a7e5e3c0-6e11-4ec4-8ef4-40690312f776&_t=gps-id:pcDetailTopMoreOtherSeller,scm-url:1007.40050.354490.0,pvid:a7e5e3c0-6e11-4ec4-8ef4-40690312f776,tpp_buckets:668%232846%238110%231995&pdp_ext_f=%7B%22order%22%3A%22244%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%7D&pdp_npi=4%40dis%21USD%213.53%213.53%21%21%213.53%213.53%21%402103010e17443081948038321e21e7%2166493995286%21rec%21US%21794602621%21X&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A)  
![image](https://github.com/user-attachments/assets/a3b275a8-7a31-4c71-afd0-53ba33865ff6)
