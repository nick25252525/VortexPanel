# VortexPanel v3.9.1

The Hosting Module is now bought and renewed with PayPal, right from the panel. One order can hold licences for several servers; each licence is linked to a server's IP address and activates by itself on that server.

## Hosting Module: buying

- **Hosting Module page, new order form:** choose 1, 6 or 12 months, the number of servers, and optionally the IP addresses of your other servers (this server's address is filled in for you). The summary shows the total and the end date; **Pay with PayPal** opens PayPal in a new window (PayPal balance or a card).
- **After the payment** the page follows the order by itself: payment received, licence linked to this server's IP, Hosting Module downloaded (signed and checked) and installed. Nothing to copy or paste. If PayPal holds a payment for a check, the page says so and the licence follows when PayPal releases it.
- **Other servers:** open Hosting Module in the panel of a server whose IP is in the order and its licence activates by itself (the panel also asks in the background every few hours). Licences bought without an IP are linked later in the licence account.
- **Renewing:** from 30 days before the end, the page shows a renewal box (1, 6 or 12 months). The time is added to the current end date. Licences are paid in advance and do not renew by themselves; an email arrives 7 days and 1 day before the end.
- **When a licence ends** the Hosting Module locks its admin side (new accounts, package changes). Customer websites, mail and the customer portal keep running.

## Licence account

- An account is made with the first purchase, for the email entered in the order. The purchase email has a link that confirms the address and sets the password.
- In the account: every licence with its server IP, status and end date; **change a licence's IP** (once every 30 days after a server has used it; the server it leaves locks the module's admin side); link licences that have no IP yet; renew several licences at once; buy more; orders and printable receipts.

## Licence rules

- A licence works only on the server IP it is linked to (the exact address, IPv4 or IPv6; the panel talks to the licence server over IPv4 when it can, so the address stays the same). A copy of a server on another address does not get the licence or module downloads.
- A reinstalled server on the same IP takes the licence over once every 30 days.
- A licence linked to an IP keeps working offline for up to 3 days without reaching the licence server, and never past its end date.
- Refunds and PayPal chargebacks end the licences of that order.
- Licence keys from earlier purchases keep working ("I have a licence key" on the Hosting Module page).

## Upgrading

Run `vortex_upgrade_3.9.1.py` on a 3.9.0 panel. Panels on 3.9.0 cannot buy licences until they are updated (they show "Licences are not on sale right now"); licences they already have keep working.
