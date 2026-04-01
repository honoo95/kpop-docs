---
label: Recommended epoch values per dataset duration
author: 
 name: Alby
 avatar: alby.webp
---

# Recommended epoch values per dataset duration

---

As requested to me personally, 
I am going to make a post talking about which epoch values are recommended for a certain dataset duration. 

This is for "original" (and similar pretrains) only!!! For OV2 you can look up ‘pre-train’ in this same forum and you should find the epoch values for that.

Please note that these are just what I found to be the best while testing. If you have constructive criticism, feel free to share it with me.

---

## A few seconds-1 minute
150-200 epochs MAX

## 2 minutes
200-300 epochs MAX

## 3 to 5 minutes
300-370 epochs MAX

## 6 to 9 minutes
320-400 epochs MAX

## 10 to 13 minutes
400-500 epochs MAX

## 14-18 minutes
500-800 epochs MAX

## 19-25 minutes
600-1000 epochs MAX

## 30 minutes and above
800-1000 epochs MAX

---

One thing you can also do is set a huge epoch number (like 1000) then stop training when you see it's overtraining, although, not everyone has the chart so this can't be convenient for everyone.