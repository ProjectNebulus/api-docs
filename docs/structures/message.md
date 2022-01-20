Message Class
==============
#Properties
>`self.content`
> 
> Type: `String`
> 
> The message content

> `self.author`
> 
> Type: [[User](User.md)]
>
> The Message Author

>`self.id`
> 
> Type: `String`
> 
> The Message id

> `.channel`
> 
> Type: [[Channel](channel.md)]
> 
> The Channel the message was sent in

#Methods

>`.edit(newtext)`
> 
> Type: `Method`
> 
> If user can edit, the message is edited to the new text

>`.delete(optional: [reason])`
>
> Type: `Method`
>
> Deletes the message