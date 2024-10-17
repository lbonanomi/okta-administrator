# okta-administrator

The below flashcard questions **did not reliably appear** on exam 2024-10-16.  
Practical questions did.  

<br><br>

Shuffle flashcards like so: `git pull; ls [0-9]*.md | shuf - | while read CARD; do grep -v "\[next\]" $CARD > $CARD.tmp && mv $CARD.tmp $CARD; echo -e "\n\n[next]($LAST)" >> $CARD; LAST=$CARD; done; git add .; git commit -m 'shuffle'; git push`
