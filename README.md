# It-support-portfolio
I’m training for a help desk role and starting Broward College’s CompTIA A+, Network+, and Security+ program. 


# Ticket 001: Audio stuck on Bluetooth earbuds after disconnecting

**Device:** iPhone 15 Pro Max, iOS 26.6
**Peripheral:** Kinglucky i121 wireless earbuds

**Reported symptom:** Audio kept routing to the earbuds after they were
disconnected and put back in their case. No sound from the phone speaker.

**Questions I asked:**
- Are the earbuds actually disconnected, or still connected inside the case?
- Is it every app, or just one?

**What I checked, in order:**
1. Bluetooth status in Control Center; toggled Bluetooth off and on — no change.
2. Restarted the iPhone — no change; audio still routed to the earbuds.

**Fix:**
1. Settings > Bluetooth > tapped (i) next to the earbuds > Forget This Device.
2. Put the earbuds back in pairing mode and re-paired them.

**Root cause:** Most likely a corrupted or stale pairing record for the
earbuds. Forgetting and re-pairing the device resolved it. Exact cause not confirmed.

**How I verified it worked:** played music with earbuds in case to confirm audio switchback. 

**Prevention / notes:** If audio gets stuck again, check the audio output
picker in Control Center first, then try Forget This Device before a restart.

**Time to resolve:** 5-7 minutes
