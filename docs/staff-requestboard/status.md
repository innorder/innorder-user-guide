---
sidebar_position: 0
---

import requestStatus from "@site/static/staff/request-status.png"

# Request Status

See how requests are color-coded by status.

<h6 style={{backgroundColor:"orange", width:120}}>Pending - Orange</h6> Waiting for staff acceptance.

<h6 style={{backgroundColor:"yellow", width:140}}>In Progress - Yellow</h6> Accepted and being worked on.

<h6 style={{backgroundColor:"#A4C2F4", width:120}}>Scheduled - Blue</h6> Scheduled by the guest; turns Pending (orange) when it’s time for action

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={requestStatus}
    alt="status by color-codes"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Status by color code</p>
</div>