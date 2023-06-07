========================
Get started with Discuss
========================

The *Discuss* app allows a company to bring all of their communication together through messages,
notes, and chat. Users are able to share information, projects, and files. Prioritize tasks and stay
connected with colleagues and partners across applications. Forge better relationships and increase
productivity and transparency by promoting a convenient way of communicating.

.. _discuss_app/notification_preferences:

Choose notifications preference
===============================

Access *preferences* by navigating to :menuselection:`Settings app --> Users --> User -->
Preferences tab`. Then choose either :guilabel:`Handle by Emails` or :guilabel:`Handle in Odoo` for
how the user's notifications should be handled.

.. image:: get_started/preferences-user.png
   :align: center
   :alt: View of the preferences page for Odoo Discuss

By default, the field is set as :guilabel:`Handle by Emails`. With this setting enabled, a
notification email will be sent by Odoo every time a message is sent, a note is sent with an '@'
mention, or a notification is sent for a record that the user follows.

By choosing :guilabel:`Handle in Odoo`, the above notifications are shown in the *Dicuss* app's
:guilabel:`Inbox`. Messages can have the following actions taken on them: respond with an emoji by
clicking :guilabel:`Add a Reaction`, or reply to the message by clicking on :guilabel:`Reply`.
Additional actions may include starring the message by clicking :guilabel:`Marked as Todo`, or
pinning the message by selecting :guilabel:`Pin` or even mark the message as unread by selecting
:guilabel:`Marked as unread`.

.. image:: get_started/reactions-discuss.png
   :align: center
   :alt: View of an inbox message and its action options in Odoo Discuss

Clicking :guilabel:`Mark as Todo` on a message causes it to appear on the :guilabel:`Starred` page,
while clicking :guilabel:`Mark as Read` moves the message to :guilabel:`History`.

.. image:: get_started/starred_messages.png
   :align: center
   :alt: View of messages marked as todo in Odoo Discuss

Start chatting
==============

The first time a user logs in to their account, OdooBot sends a message asking for permission to
send desktop notifications for chats. If accepted, the user will receive push notifications on their
desktop for the messages they receive, regardless of where the user is in Odoo.

.. image:: get_started/odoobot_push.png
   :align: center
   :alt: View of the messages under the messaging menu emphasizing the request for push
         notifications for Odoo Discuss

.. tip::
   To stop receiving desktop notifications, reset the notifications settings of the browser.

To start a chat, go to the :menuselection:`Discuss` app and click on the :guilabel:`+` icon next to
:guilabel:`Direct Messages` or :guilabel:`Channels` in the left menu of the dashboard.

.. image:: get_started/channels_direct_messages.png
   :align: center
   :height: 400
   :alt: View of Discuss’s panel emphasizing the titles channels and direct messages in Odoo Discuss

A company can also easily create :doc:`public and private channels <team_communication>`.

Mentions in the chat and on the chatter
---------------------------------------

To mention a user within a chat or the chatter, type *@user-name*; to refer to a channel, type
*#channel-name*. The user mentioned will be notified in their *Inbox* or through an email, depending
on their communication settings.

.. image:: get_started/chat_windows.png
   :align: center
   :alt: View of a couple of chat window messages for Odoo Discuss

.. tip::
   When a user is mentioned, the search list (list of names) suggests values first based on the
   task’s followers, and secondly on *Employees*. If the record being searched does not match with
   either a follower or employee, the scope of the search becomes all partners.

User status
-----------

It is helpful to see what colleagues are up to and how quickly they can respond to messages by
checking their *status*. The status is shown on the left side of a contact’s name on the *Discuss*
sidebar, on the *Messaging menu* and when listed in the *chatter*.

- Green = online
- Orange = away
- White = offline
- Airplane = out of the office

.. image:: get_started/status.png
   :align: center
   :height: 300
   :alt: View of the contacts’ status for Odoo Discuss

.. seealso::
   - :doc:`team_communication`
   - :doc:`plan_activities`
