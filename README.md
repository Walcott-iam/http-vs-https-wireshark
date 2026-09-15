# http-vs-https-wireshark
# Wireshark: HTTP vs HTTPS — Why Encryption Matters

A hands-on packet capture experiment demonstrating how HTTP sends
credentials in **plain text**, while HTTPS encrypts everything.

## 🔍 Background

After I shared my previous tech project on LinkedIn, someone commented:

> "You should run the same capture against HTTPS and HTTP"

I finally did it. Here's what I found.

## 🧪 The Experiment

### Step 1 — The Unsecure Website (HTTP)
I filled a form on an HTTP-only website and captured the traffic with Wireshark.

**Result:** My credentials showed up as **plain text** — fully readable.

![Unsecure Website](images/unsecure-website.png)

### Step 2 — The Secure Website (HTTPS)
Then I logged into an HTTPS website and captured the same traffic.

**Result:** Everything was **encrypted** — scrambled and unreadable.

![Secure Website](images/secure-website.png)

## 💡 The Lesson

- **HTTP** sends your data like a postcard — anyone on the network can read it.
- **HTTPS** sends your data like a locked box — only the destination can open it.

This is exactly why HTTPS is not an option anymore — it's a requirement.

## 🛠️ Tools Used
- **Wireshark**
- Filter used: `tcp.stream eq 22` (unsecure) and `tcp.stream eq 30` (secure)



## 🔗 Original LinkedIn Post
[Read the full post here →](# Wireshark: HTTP vs HTTPS — Why Encryption Matters

A hands-on packet capture experiment demonstrating how HTTP sends
credentials in **plain text**, while HTTPS encrypts everything.

## 🔍 Background

After I shared my previous tech project on LinkedIn, someone commented:

> "You should run the same capture against HTTPS and HTTP"

I finally did it. Here's what I found.

## 🧪 The Experiment

### Step 1 — The Unsecure Website (HTTP)
I filled a form on an HTTP-only website and captured the traffic with Wireshark.

**Result:** My credentials showed up as **plain text** — fully readable.

![Unsecure Website](images/unsecure-%20website.png)

### Step 2 — The Secure Website (HTTPS)
Then I logged into an HTTPS website and captured the same traffic.

**Result:** Everything was **encrypted** — scrambled and unreadable.

![Secure Website](images/secure-%20website.png)

## 💡 The Lesson

- **HTTP** sends your data like a postcard — anyone on the network can read it.
- **HTTPS** sends your data like a locked box — only the destination can open it.

This is exactly why HTTPS is not an option anymore — it's a requirement.

## 🛠️ Tools Used
- **Wireshark**
- Filter used: `tcp.stream eq 22` (unsecure) and `tcp.stream eq 30` (secure)


## 🔗 Original LinkedIn Post
[Read the full post here →](https://www.linkedin.com/posts/oresanya-khaleed-walcott_cybersecurity-wireshark-infosec-activity-7493025516996771840-8qQQ?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFmaJ1cBdofeb1p9_fn4yuUU1OlUbxxv-UQ)

## ⚠️ Disclaimer
All captures were performed on my own test accounts using fake credentials,
for educational purposes only.)

## ⚠️ Disclaimer
All captures were performed on my own test accounts using fake credentials,
for educational purposes only.
