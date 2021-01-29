# README

# Contents

- Introduction
- Prerequisites
- Installing the payment module
- License

# Introduction

This Ubercart module provides an easy method to integrate with the payment gateway.
 - The plugin directory contains the files that need to be uploaded to the root of your Ubercart installation
 - Supports Drupal versions: **8.0+**

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php
    - SSL **NB: HTTPS is expected to be in place as the payment gateway will respond over SSL when redirecting the user's browser. Failure to provide an environment where HTTPS traffic is possible, will result in the 3DSv2 payment flow failing***

> Please note that we can only offer support for the Module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarentee normal functionality if unsupported changes are made.

# Installing and configuring the module

1. Unzip and upload the plugin folder to your root directory
2. Activate the module 'Payment Network' through the 'Extend' menu in Drupal
3. Go to Store -> Payment methods -> and find 'ADD PAYMENT METHOD' section
4. Find Payment Network Hosted Integration from select, and add it
5. Configure settings to complete the process of adding payment method
6. Click 'Save'

License
----
MIT
