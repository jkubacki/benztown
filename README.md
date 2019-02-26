# Benztown
Audio elements manager for music​ ​production library company (MPLC).

## Backend - Admin Panel & API
https://github.com/jkubacki/benztown-api

## Frontend - Client browser
https://github.com/jkubacki/benztown-frontend

## Info & Disclaimers

I decided to add extra feature of inviting clients, sending invitation email and confirming account on the frontend.
It's out of MVP. Wouldn't implement it if I had a fixed time budget. But it nicely shows the way I write my services in Ruby.

I intentionally included encryption keys for development and tests so I don't have to share them with you.
There are no sensitive data inside. If there were (e.g. development api secret key) I wouldn't share it.

It would be nice to have pagination on the backend and frontend. But that's another out of MVP feature.

In MVP i decided to implement app for one MPLC. It would be pretty straightforward to extend it to handle multiple MPLCs.

In production setting I would setup a proxy from frontend to pass requests to the backend for admin panel.
