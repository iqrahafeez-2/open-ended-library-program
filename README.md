	//TASK 1
	string book_name=" ";
	char person_choice;
	int days=0,issue_date,return_date,Total_days;
		cout<<"Enter the book you want to issue: ";
		getline(cin,book_name);
 	cout<<"Issue date: ";
		cin>>issue_date;
		cout<<"Return date: ";
		cin>>return_date;
		Total_days=return_date-issue_date;
		cout<<"Total days after issuance: "<<Total_days;
//Fine will be charged after 7 days of issuance
 days= Total_days-7;
 cout<<"\nDays on which fine is applied: "<<days;
cout<<"\nFine: "<<days*1<<"$";

return 0;
}
