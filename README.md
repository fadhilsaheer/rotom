# ROTOM

Simple SMS broker

## Context

Currently all SMS providers are expensive, for example twillio charges about $0.0079 per SMS. This will be a problem for indie developers, who just want to release their product with zero cost. Most of us don't use phone verification because of this. And go with email & password auth making it another big headache in the future. Even if we use phone most of us will only have around 10k sms max (you're lucky for even getting 100users tho). That would cost around $79. We all have a spare mobile phone, and nowadays there are many sim plans with unlimited sms, which wont even cost a dollar, so why don't we use that both to send sms from our phones.

## Idea

Run ROTOM service in your backend (lightweight rust service). Install ROTOM mobile app and connect it to ROTOM service which is running in your backend. When you send SMS using ROTOM service, the mobile phone will send SMS accordingly.
