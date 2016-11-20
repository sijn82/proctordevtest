
After 2 days trying to get ansible etc working on my windows 10 machine, I had to give up and use an alternative method.  Now it's just in a simple scotchbox vm.  I've created an up to date database-dump.sql which is in the public folder.

Instructions:

Download files, navigate to directory, vagrant up,  vagrant ssh and mysql -u root -p root and install database-dump.sql. Go to proctorsdevtest.local or 192.168.33.10 and you should be able to navigate the site.  Login username and password is still superuser.

Excuses:

I thought I'd completed steps 1/extended and 2/extended until I realised I was unable to use the 'Store' content type to limit how you 'Viewed' the content.  It also meant that I couldn't reposition the fields in the appropriate blocks.  Or at least not within the time constraints.  It must be something to do with the programmatically created nodes because I can manually add them to the content type and manipulate their position just fine.

I would like to add that question 3/extended would have been perfectly doable had I been able to resolve this issue. I would also like to apologise for the general performance of my submit module, I was planning to look into that at the end.

They do however filter appropriately and so the functionality of question 2 is there.  They also check whether the node already exists and otherwise create them, along with their lat/long coordinates, so that functionality is also present.

Thanks for the challenge though, I really enjoyed it.