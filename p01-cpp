    #include<string>
    #include<iostream>
    #include<ctime>
    #include<cstdlib>
    using namespace std;

    main()
    {
        double srand( time(NULL) );
        int rnum;
        int num;
        char dif;
        int game=1;
        while (game==1)
        {
        cout<< "select difficulty. h for high m for medium l for low"<< endl;
        cin>>dif;
        if( dif== 'm')
        {
        rnum = rand() % 10 + 1;
        cout<<"Try and guess the random number between 1 and 10"<<endl;
        }
        else if(dif == 'l')
        {
        rnum = rand() % 2 + 1;
        cout<<"Try and guess the random number between 1 & 2"<<endl;
        }
        else if( dif == 'h')
        {
        rnum = rand() % 100 + 1;
        cout<<"Try and guess the random number between 1 & 100"<<endl;
        }
        cin >> num;

        if( num < rnum )
        {
           cout << "You were low by "<< rnum - num << ". You lose "<<endl;
        }
        if( num > rnum )
        {
           cout << "You were high by "<< num - rnum << ". You lose "<<endl;
        }
        if( num==rnum)
        {
           cout << "You win the number was "<< num<< "."<< endl;
        }
        cout << "Would you like to play again. if yes type 1 if no type 2."<< endl;
        cin >> game;
        }
        return 0;
   }
        
