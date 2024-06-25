public class ContactSearch {
    
    public static List<Contact> searchForContacts(String lastName, String maillingpostalCode){
        
        List<Contact> contactList = [Select Id,Name from Contact where
                                  LastName =: lastName and 
                                  MailingPostalCode =: maillingpostalCode];
        return contactList;
    }

}