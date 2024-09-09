---
date: 8-Sep-2024
---

# AREDN Nodes

These are my notes on what nodes/services I would want to setup for an EMCOMM situation.

## AREDN Nodes

### AREDN node 1
one main node attached to a smart switch this provides the 5ghz connection to the wireless clients.  
    
this node will advertise the services behind it:

    - PBX
        - freepbx
    - Matrix
    - email
        - mailcow
    - FileBrowser
    - mapping server
    - authentication provider?

### AREDN node 2
a P2P node attached to that switch on VLAN 2 for DtD and providing a connection to the rest of the mesh.

---

## notes on setup

- This will all need to be ansible based for configuration

---

## power

This will need to have 24v and 12v power available to it. The Ubiquiti devices all run on 24v power, and can be easily setup with wiring.

I want this to be a modular setup, one box is power, one box is our node, one box can be our networking and another box can be our services.

The batteries should be rechargeable, whether these are dewalt batteries, milwaukee, or something else.

I would like to use Li-Ion batteries as they have the best density, and won't make the boxes to heavy.

### boxes

Packout would be great for this, but they are expensive. I will look into the hart boxes to see if they are cheaper, and of decent quality.

### solar

It would be nice to have one of these boxes also hold a solar charge controller that could then make this 100% sustainable for long term use.