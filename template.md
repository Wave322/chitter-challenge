As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a Maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

nouns: chitter, peeps, time, users

chitter,
user_id, username,


peeps,
peeps_id, peeps_time, username (of poster)


CREATE TABLE chitter (
  id SERIAL PRIMARY KEY,
  username text,
  peeps text,
  peeps_time text
);


