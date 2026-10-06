---
title: Join a family
permalink: /join/
---

# You've been invited to a family in Receiptly

<p>
  <a id="open-app" href="#" style="display:inline-block;padding:12px 20px;background:#0f5c4d;color:#fff;border-radius:10px;text-decoration:none;font-weight:600;">Open in Receiptly</a>
</p>
<p id="open-note" style="font-size:0.95em;color:#555;display:none;">Nothing happened? You don't have Receiptly on this phone yet — get it below, then tap the link in the message again.</p>
<script>
  // The invitation rides in the URL fragment, which never reaches this
  // page's server. The button hands it to the app through its own scheme,
  // for the case where iOS opened this page in Safari instead of the app.
  (function () {
    var token = (location.hash || "").replace(/^#/, "");
    var button = document.getElementById("open-app");
    var note = document.getElementById("open-note");
    if (!token) { button.style.display = "none"; note.style.display = "none"; return; }
    button.setAttribute("href", "receiptly://join#" + token);
    // If the app is here, it has taken over by now; otherwise say what to do.
    button.addEventListener("click", function () {
      setTimeout(function () { note.style.display = "block"; }, 1500);
    });
  })();
</script>

**If you don't have Receiptly yet:** install it from the
[Get Receiptly page](/get/), then come back to the invitation message and tap
its link again, or enter the code in the app under Family → Join family.

**If Receiptly is installed:** tap **Open in Receiptly** above. Or open the
app, go to the Family tab, tap Join family, and paste the invitation message
(the app picks out the code).

Invitations are for one person and expire after seven days. Only receipts
members choose to share are visible to the family. Nothing from your own
receipts is shared by joining.

[Privacy Policy](/) · [Support](/support)
