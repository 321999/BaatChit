# what is BaatChit media app 
 * A SOSCIAL MEDIA APP IS PLACE WHERE USER CAN SHARE THEIR LIVES WITH OTHERS 
FOR THIS USER MUST LOGIN TO VIEW THE OR  CREATE THE POST .A USER WILL BE ABLE TO LOGIN THEONLY IF THE  THEY REGISTER ON TH SM .tHE USER WILL BE ABLE TO SHSRE ABOU T THERMSELVES IN THE FORMAT OF POST OAND A POSTE WILL INCLUSED AN IMAGE ANED SOME TEXT ALLL THE USER WILL BE ABLE SHARE ANY NUMNBER O FPOSTE THE CANLLKE USER UPOST .U SUER CAN FOLLOW OTHER USERS TO VIEW THYERI POSTTS S.; a USER CAN LLIKE ANOTHER USER POST AND COMMNENT ON ON IT . tHE SUER HLULD BE ABGLE TO MESSAGE ANOTHER USER POST AND ON IT .tHE USER HLULD ABLE TO MESSAGE ANOTHER  USER ANDL REPLY 

first module 
USER module 
WHERE USER CAN PERFORM CRUD OPERATION CRETE_THEIR_PROFILE,LIKE,COMMNENT,FOLLOW 

Auth module 
register,login protected route[where user can access after login only]

posts
resource,like comment caption resend vhaireplytoThePost send_the_post 

follow
follow is the different resource onthe server 
follow who can follow the other users 

messaging 

news feed 
recent posts will be shown 
and the user to whom he follows he can see teh recent post of them or in his absent which recent posts are there 

##### what are the tables or schemas we should define for each entities 

Users Table 
user_id(primary,string)  username(string,UNIQUE)  password(string,hashed) email(string,unique) 
create_user  update_user  delete_posts  retrieve_info_about_other_user 

posts table 
user_id(string)   post_id(string,primary kye)    caption(string)  image_url(string)   time_stamp(string)
like(int)    comment(string)  caption resend(strign,)

comment_table 
comment_id(string) || post_id(string) ||  text(string) ||  activity_id(string) || reply_text(string) ||  time_stamp(date_time)
 