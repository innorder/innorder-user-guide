---
sidebar_position: 0
---

import enableDisableRS from "@site/static/admin/rs/enable-disable-rs.png"
import userAcceptance from "@site/static/admin/rs/user-acceptance-checkbox.png"
import pendingCancellations from "@site/static/admin/rs/pending-cancellations.png"
import eta from "@site/static/admin/rs/eta.png"
import timeCategory from "@site/static/admin/rs/time-based-category.png"
import selectType from "@site/static/admin/rs/select-type.png"
import minMaxChoice from "@site/static/admin/rs/min-max-choice.png"
import applyOption from "@site/static/admin/rs/apply-option.png"
import createUpsell from "@site/static/admin/rs/create-upsell.png"
import customUpsellCheckout from "@site/static/admin/rs/custom-upsell-checkout.png"
import editTranslation from "@site/static/admin/rs/edit-translation.png"

# Room Service

## Settings

**Enable/Disable Service:** Toggle Room Service on/off. If off, guests won’t see it when scanning the QR code.

**Time-Based Availability:** Set specific times for when guests can place orders. When outside the available time range, it will show as “unavailable” to guests.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={enableDisableRS}
    alt="how to enable/disable room service"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Toggle Room Service on/off & set time range</p>
</div>

**Message to Guest:** Enter a custom message for guests.

**User Acceptance Checkbox:** Require guests to agree to “I understand orders are final and cannot be canceled once confirmed” before ordering.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={userAcceptance}
    alt="how to enable/disable user acceptance checkbox"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>User Acceptance Checkbox</p>
</div>

**Allow Pending Status Cancellations:** Let guests cancel pending orders if staff have not accepted it yet.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={pendingCancellations}
    alt="how to enable/disable guest cancellations"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Guests have the option to cancel Pending requests</p>
</div>

**ETA:** Provide guests with an estimated time of order completion. Staff must input an ETA when accepting an order.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={eta}
    alt="ETA settings"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>ETA</p>
</div>

**Service Charge & Tax:** Enter applicable percentages.

**Rounding Rules:** Set any rounding rules if needed.

**Void Reason:** Staff must select a void reason when voiding an item. Pre-created reasons include Out of Stock, Kitchen Error, Customer Error. You can add, edit, or delete reasons.

**Payment Method:** Guests choose a payment method (e.g., bill to room, cash). Add, edit, or delete methods here.

## Creating & Editing the Menu

**Categories:** Organize menu items by creating categories. Use “+ Create Category” to add new ones. Enable time-based availability if needed (e.g., Breakfast available from 7 AM to 10 AM).

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={timeCategory}
    alt="a category with time-based settings"
  />
</div>

**Items:** Add menu items within categories. Use “+ Create Item” to upload an image, name the item, set a price, and optionally add a description. Add options as needed.

**Select Type:** Choose between Food or Beverage for report categorization.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={selectType}
    alt="selecting an item type"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Select Food or Beverage</p>
</div>

## Options

Allow guests to customize menu items by creating options.

**Create Option:** Name the option and decide if it's required.

**Min/Max Choices:** Set the range of choices guests can select. For example, if you set Min # to 1 and Max # to 3, guests must choose at least one option and can choose up to three.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={minMaxChoice}
    alt="setting up choices"
  />
</div>

**Choices:** Name each choice, set prices, or mark as free.

**Apply to Menu Items:** Select applicable items for these options.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={applyOption}
    alt="applying the option to menu items"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Apply to the option to menu items</p>
</div>

## Upsell

**Upsell on Items:** Create upsell categories (e.g., “Thirsty? 🍹”) and add items. Then apply this upsell to specific menu items.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={createUpsell}
    alt="creating an upsell"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Creating Upsells</p>
</div>

**Upsell at Checkout:** Toggle on to display top-selling or customized items at checkout.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={customUpsellCheckout}
    alt="custom upsell at checkout"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Upsell at Checkout</p>
</div>

## Translations

**Translations:** Menu entries will be automatically translated to other languages enabled in your settings. Double-check accuracy, edit as needed, or sync to auto-translate again.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: '20px', marginBottom: '20px' }}>
  <img
    src={editTranslation}
    alt="editing translations"
  />
  <p style={{ marginTop: '10px', fontSize: '14px', color: '#555' }}>Click the check to save changes or x to cancel</p>
</div>
