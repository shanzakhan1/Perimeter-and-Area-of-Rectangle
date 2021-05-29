# Perimeter-and-Area-of-Rectangle

    #include <iostream>
    using namespace std;

    int main()
    {
    	int width, length, area, perimeter;
        cout<<" Input the length of the rectangle : ";
    	cin>>length;
		cout<<" Input the width of the rectangle : ";
    	cin>>width;
    	area=(length*width);
		perimeter=2*(length+width);
        cout<<" The area of the rectangle is : "<< area << endl;
        cout<<" The perimeter of the rectangle is : "<< perimeter << endl;		
        cout << endl;
        return 0;
    }
