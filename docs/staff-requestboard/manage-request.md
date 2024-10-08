---
sidebar_position: 1
---

import acceptRequest from "@site/static/staff/accept-request.png"
import eta from "@site/static/staff/eta.png"
import completeRequest from "@site/static/staff/complete-request.png"
import voidRequest1 from "@site/static/staff/void-request1.png"
import voidRequest2 from "@site/static/staff/void-request2.png"
import voidRequest3 from "@site/static/staff/void-request3.png"
import translation from "@site/static/staff/translation.png"

# Request Management

Manage requests by accepting, completing, or voiding them.

**Accept a Request:** Click the **Pending (orange)** request, then click **Accept**. If prompted, provide an **ETA** (managed in the Admin Dashboard).

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={acceptRequest}
    alt="accepting a request"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Accept request</p>
</div>

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={eta}
    alt="eta"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Enter an ETA</p>
</div>

**Complete a Request:** Click **Complete** when done. The request will be removed from the **Request Board** but saved in **History**.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={completeRequest}
    alt="completing a request"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Complete request</p>
</div>

**Void a Request:** Click the **trash icon**, select a reason, then click **Void**.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={voidRequest1}
    alt="void request"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Void request by clicking the trash icon</p>
</div>

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={voidRequest2}
    alt="voiding a request"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Select Void Reason</p>
</div>

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={voidRequest3}
    alt="voiding a request"
  />
    <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Voided request</p>
</div>

**Guest Cancellations:** If enabled, guests can cancel a **Pending** request, which will then be marked as **“Guest Cancel”**.

**Translations:** Click the **translation icon** to translate guest notes.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={translation}
    alt="translating guest note"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Translate guest note</p>
</div>
