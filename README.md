# Intro melody with fade-in and fade-out
# faded in 
with gain(value=[0, 1], beats=1, start=0):
    playNote(70, beats=0.5, velocity=96, sustain=0.10)
    playNote(72, beats=0.5, velocity=96, sustain=0.10)
playNote(74, beats=1.0, velocity=98, sustain=0.20)
rest(0.5)
playNote(72, beats=0.5, velocity=94, sustain=0.10)
playNote(70, beats=1.0, velocity=92, sustain=0.20)
# faded out
with gain(value=[1, 0], beats=2, start=0):
    playNote(70, beats=2, velocity=90, sustain=0.30)


    #Chorus Section Notes
# These notes represent the main vocal melody of the chorus 
# ("It’s been a long day – without you, my friend"), 
# which serves as the emotional center of the song.
moveTo(7)
# It's been a long day — with- out you, my friend
rest(0.5)                                            
playNote(62, beats=0.5, velocity=100, sustain=0.00) # D4, 1/8 "It's"
playNote(60, beats=0.5, velocity=98,  sustain=0.00) # C4 , 1/8"been"
playNote(62, beats=0.5, velocity=100, sustain=0.10) # D4 , 1/8 "a" 
playNote(65, beats=0.5, velocity=95,  sustain=0.00) # F4 , 1/8 "long" 
playNote(65, beats=1.0, velocity=100, sustain=0.20) # F4 , 1/4 "day"
playNote(67, beats=1.0, velocity=100, sustain=0.00) # G4 , 1/4 "with–"
playNote(65, beats=0.5, velocity=95,  sustain=0.10) # F4 , 1/8 "out"
playNote(67, beats=0.5, velocity=92,  sustain=0.00)  # G4 , 1/8 "you"
rest(0.5)
playNote(60, beats=0.5, velocity=100, sustain=0.05) # C4, 1/8  "my"
playNote(60, beats=0.5, velocity=98,  sustain=0.00) # C4, 1/8  "friend" 
playNote(58, beats=0.5, velocity=100, sustain=0.00) # Bb3, 1/8  pause 
playNote(60, beats=0.5, velocity=100, sustain=0.00) # C4, 1/8  melodic hold
playNote(62, beats=2.0, velocity=96,  sustain=0.50) # D4, 1/2  sustained “friend”

# and I’ll tell you all a-bout it when I see you a-gain
rest(0.5)                                           
playNote(62, beats=0.5, velocity=100, sustain=0.00) # D4, 1/8 "and"
playNote(65, beats=0.5, velocity=104, sustain=0.00) # F4, 1/8 "I’ll"
playNote(67, beats=1.0, velocity=104, sustain=0.05) # G4., dotted 1/4 "tell"
playNote(69, beats=1.0, velocity=96,  sustain=0.00) # A4, 1/4 "you"
playNote(67, beats=0.5, velocity=92,  sustain=0.10) # G4, 1/8 "all"
playNote(65, beats=0.5, velocity=90,  sustain=0.00) # F4, 1/8  "a-"
playNote(62, beats=1.0, velocity=100, sustain=0.00) # D4, 1/4 "bout"
playNote(60, beats=0.5, velocity=100, sustain=0.05) # C4, 1/8 "it"
playNote(60, beats=0.5, velocity=98,  sustain=0.00) # C4, 1/8 "when"
playNote(58, beats=0.5, velocity=100, sustain=0.15) # Bb3, 1/8"I"
playNote(62, beats=1.5, velocity=100, sustain=0.50) # D4, 1/8 "see"
playNote(60, beats=0.5, velocity=98,  sustain=0.00) # C4, 1/8 "you"
playNote(60, beats=0.5, velocity=96,  sustain=0.00) # C4, 1/8 "a-"
playNote(63, beats=0.25, velocity=92, sustain=0.05) # Eb4 1/16 "gain"
playNote(62, beats=1.5, velocity=96, sustain=0.40)  # D4,dotted 1/4 hold “again”
playNote(60, beats=0.5, velocity=95,  sustain=0.10) # C4,1/8 soft release
playNote(58, beats=0.5, velocity=92,  sustain=0.20) # Bb3,1/8 end pause
rest(1.0)

# We've come a long way from where we began
playNote(60, beats=0.5, velocity=100, sustain=0.00) # C4 1/8 "We've"
playNote(60, beats=0.5, velocity=98,  sustain=0.05) # C4 1/8 "come"
playNote(62, beats=0.75, velocity=100, sustain=0.10) # D4,1/4 "a"
playNote(67, beats=1.0, velocity=98,  sustain=0.30) # G4, 1/4 "long"
playNote(65, beats=1.0, velocity=96,  sustain=0.30) # F4, 1/8 "way"
playNote(62, beats=1.0, velocity=96,  sustain=0.30) # D4,1/4 "from"
playNote(60, beats=1.0, velocity=96,  sustain=0.30) # C4,1/8 "where"
rest(0.5)
playNote(62, beats=0.5, velocity=100, sustain=0.00) # D4,1/8 "we"
playNote(65, beats=1.0, velocity=98, sustain=0.20)  # F4, 1/4 "be-"
playNote(58, beats=0.5, velocity=100, sustain=0.60) # Bb3 1/8 "gan"
playNote(67, beats=0.5, velocity=96,  sustain=0.20) # G4, 1/4 end of phrase
rest(0.5)                                          

# Oh, I'll tell you all about it when I see you again, when I see you again
rest(0.5)
playNote(60, beats=0.5, velocity=98, sustain=0.05)   # D4 1/8 "Oh"
playNote(62, beats=0.5, velocity=100, sustain=0.10)  # F4 1/8 "I'll"

# tell you all a-bout it when I see you a-gain
playNote(65, beats=0.5, velocity=104, sustain=0.00) #F4, 1/8 "tell"
playNote(67, beats=0.5, velocity=104, sustain=0.05) #G4, 1/8 "you"
playNote(69, beats=1.0, velocity=104, sustain=0.05) #A4, 1/4 "all"
playNote(67, beats=0.5, velocity=98,  sustain=0.05) #G4, 1/8 "a-"
playNote(65, beats=0.5, velocity=96,  sustain=0.05) #F4, 1/8 "bout"
playNote(62, beats=0.5, velocity=95,  sustain=0.05) #D4, 1/8 "it"
playNote(60, beats=0.5, velocity=96,  sustain=0.10) #C4, 1/8 "when"
playNote(62, beats=0.5, velocity=100, sustain=0.10) #D4, 1/8 "I"
playNote(65, beats=0.5, velocity=100, sustain=0.10) #F4, 1/8 "see"
playNote(67, beats=0.5, velocity=98,  sustain=0.05) #G4, 1/8 "you"
playNote(65, beats=1.0, velocity=96,  sustain=0.30) #F4, 1/4 "a-"
playNote(63, beats=1.0, velocity=92,  sustain=0.40) #E♭4,1/4 "gain"
rest(0.5)

# when I see you again (with fade out)
with gain(value=[1.0, 0.8, 0.55, 0.3, 0.1, 0.0], beats=4.5, start=0):
    # Fade level 1.0 → full volume
    playNote(62, beats=0.5, velocity=100, sustain=0.10) #D4. 1/8 “when”
     # Fade level 0.8 → slightly softer
    playNote(65, beats=0.5, velocity=100, sustain=0.10) #F4, 1/8 “I”
    # Fade level 0.55 → medium fade
    playNote(67, beats=0.5, velocity=98,  sustain=0.05) #G4, 1/8 “see”
    # Fade level 0.3 → noticeably quieter
    playNote(65, beats=1.0, velocity=96,  sustain=0.30) #F4, 1/8 “you”
    # Fade level 0.1 → very soft
    playNote(63, beats=1.0, velocity=92,  sustain=0.40) #Eb4,1/4 “a-”
    # Fade level 0.0 → silence at the end
    playNote(58, beats=1.0, velocity=90,  sustain=0.60) #Bb3,1/4 “gain”
rest(0.5)


# Bass Track section (from beats 24 to 92)
# This bass track adds depth and rhythmic support to the chorus
# Root-note bass with fade-in & fade-out to create a smooth dynamic flow that feels natural
# faded in during the first 4 beats
moveTo(8)
with gain(value=[0.4, 0.7, 1.0], beats=4, start=0):
    playNote(58, beats=2, velocity=78, sustain=0.30)  
    playNote(58, beats=2, velocity=78, sustain=0.30)
# no faded in in the following 4 beats
playNote(58, beats=2, velocity=80, sustain=0.30)
playNote(58, beats=2, velocity=80, sustain=0.30)

# Gm7 (8 beats)
playNote(55, beats=2, velocity=82, sustain=0.35)       
playNote(55, beats=2, velocity=82, sustain=0.35)
playNote(55, beats=2, velocity=82, sustain=0.35)
playNote(55, beats=2, velocity=82, sustain=0.35)

# Eb (8 beats)
playNote(51, beats=2, velocity=80, sustain=0.35)   
playNote(51, beats=2, velocity=80, sustain=0.35)
playNote(51, beats=2, velocity=80, sustain=0.35)
playNote(51, beats=2, velocity=80, sustain=0.35)

#Bb (8 beats)
playNote(58, beats=2, velocity=82, sustain=0.35)
playNote(58, beats=2, velocity=82, sustain=0.35)
playNote(58, beats=2, velocity=82, sustain=0.35)
playNote(58, beats=2, velocity=82, sustain=0.35)

# F (8 beats) 
playNote(53, beats=2, velocity=80, sustain=0.35)     
playNote(53, beats=2, velocity=80, sustain=0.35)
playNote(53, beats=2, velocity=80, sustain=0.35)
playNote(53, beats=2, velocity=80, sustain=0.35)

# Gm7 (8 beats) 
playNote(55, beats=2, velocity=80, sustain=0.35)
playNote(55, beats=2, velocity=80, sustain=0.35)
playNote(55, beats=2, velocity=80, sustain=0.35)
playNote(55, beats=2, velocity=80, sustain=0.35)

#Eb (8 beats)
playNote(51, beats=2, velocity=78, sustain=0.35)
playNote(51, beats=2, velocity=78, sustain=0.35)
playNote(51, beats=2, velocity=78, sustain=0.35)
playNote(51, beats=2, velocity=78, sustain=0.35)

#  Bb +  F
playNote(58, beats=2, velocity=78, sustain=0.35)       
playNote(58, beats=1, velocity=78, sustain=0.25)      
# faded out from 83 beats to the end
with gain(value=[1.0, 0.6, 0.3, 0.0], beats=8, start=0):
    #beats 83-88, Bb
    playNote(58, beats=2, velocity=76, sustain=0.30)   
    playNote(58, beats=2, velocity=74, sustain=0.30)   
    playNote(58, beats=1, velocity=72, sustain=0.20)   
    #beats 88 to the end, F
    playNote(53, beats=2, velocity=70, sustain=0.25)   
    playNote(53, beats=1, velocity=65, sustain=0.15
