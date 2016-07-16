# 2016 T2TRG RIOT summit meeting

Date: 16.7.2016
Time: 13:00-19:00

## Topics
We are generally interested in:

- what are the plans for ongoing implementations
- what is out there already
- what did we learn
    - about implementation approaches
    - about the protocols (and how they should be improved)

## Draft (and dynamic) agenda 

### 13:00-14:40 General

- Call to action on better IoT software on devices
- Turn-key software framework/stack for constrained IoT devices
- Memory management strategies

### Break

### 15:00-16:15 CoAP implementation experiences

- Experience implementing CoAP
   - Erbium (Matthias Kovatsch)
   - microcoap: Sebastian + Lennart
   - libcoap: Olaf
- demo: RIOT+Microcoap (Sebastian)
- discuss Experience using it in the application's setting, APIs... "thinking in application categories"...

### Break

### 16:35 Web of Things

- Thing-to-thing intro (vs. funnel everything through China)
- Things as servers + drive interaction as a client

How do we structure the interfaces offered by our devices?

- W3C Thing descriptions (Matthias K) 
- Structuring implementations around Hypermedia controls
- Klaus/Michael -> Coral/HSML (Michael)


### ~17:00- Data formats

Experience with data formats and their implementations

- CBOR
- SenML (Ari & Lennart)

### Header compression

- RFC 7400 GHC for DTLS and other applications (Stefan Schmidt)
- Robust (ROHC) vs. area context (6Lo) vs. static (SCHC) header
  compression (Alex, Krishna?)

### Security

- Crypto infrastructure (Crypto Provider API), hardware support
- Protocols on top of that
    - tinydtls (Olaf?)
    - object security (Kepeng Li? Francesca?)
- Application support (including authorization?)
- Lifecycle model; Software updates/OTA (Ludwig)

### Flex time, wrapup

- anything else that came up during the discussions?
- next steps...
