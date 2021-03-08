---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Contato
<?php

return [
    'subject' => [
        'prefix' => '[Contact Form]'
    ],
    'emails' => [
        'to'   => '',
        'from' => ''
    ],
    'messages' => [
        'error'   => 'There was an error sending your message, please try again later.',
        'success' => 'Your message has been sent successfully.'
    ],
    'fields' => [
        'name'     => 'Name',
        'email'    => 'Email',
        'phone'    => 'Phone',
        'subject'  => 'Subject',
        'message'  => 'Message',
        'btn-send' => 'Send'
    ]
];
