//Update Records in Salesforce via Execute Anonymous

PushTopic p = new PushTopic(Id='0IF02000000GnO7GAK', NotifyForFields = 'Select'); 
update(p);

//Change a Password for a user

System.setPassword(userid, password);


