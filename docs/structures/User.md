User Class
==========
>`self.username`
>
> Type: `String`
> 
> Gets the Username of the user targeted

>`self.email`
> 
> Type: `String`
> 
> Get the targeted user's email

>`self.avatar`
>
> Type: `Object`
> 
> The Avatar object of the user
> 
>> >`self.url`
>>
>> Type: `String`
>>
> >The URL of the user's avatar

> >`self.size`
>>
> >Type: `Object`
>>
> >>`self.x`
> >>
> >>Type: `Integer`
> >>
> > >The size of the image on the x axis
>>
> >>`self.y`
> >>
> >>Type: `Integer`
> >>
> >> The size of the image on the y axis


>`self.courses`
> 
> Type: `Array`
> 
> The list of all course objects of a user
> 
> Contains: `Object`
> 
> [Course Object](courses.md)

>`self.premium`
> 
> Type: `Object`
> 
> The object class of the user's premium status
> >`.isStaff`
> >
> >Type: `Boolean`
> >
> > Checks if the user is a Nebulus staff member
> 
> >`.premium`
> >
> >Type: `Boolean`
> >
> >Checks if the user has premium

>`self.bio`
> 
> Type: `Object`
> 
> The about data of the user
>>`.status`
>>
>>Type: `Object`
>>
>> Status of the user
>>>`.icon`
>>>
>>>Type: `TBD`
>>>
>>>`String` The Icon status of the user
>>
>>>`.display`
>>>
>>>Type: `String`
>>>
>>>The current displaying status of the user
