//---------------------------------------------------------------------------
#include <vcl\vcl.h>
#pragma hdrstop
 #include <String>
#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma resource "*.dfm"
TForm1 *Form1;
void play_computer();
void check_winner(int a);
void enable_box();
int r;
int count;
int img1, img2,img3,img4,img5,img6,img7,img8,img9;

//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
	: TForm(Owner)
{
}
//---------------------------------------------------------------------------
void __fastcall TForm1::FormCreate(TObject *Sender)
{
  enable_box();

}

void __fastcall TForm1::Image1Click(TObject *Sender)
{
count++;
if(count<5){
Image1->Picture= Image10->Picture;
img1=1;
Image1->Enabled= false;
 check_winner(1);
 play_computer();

 }

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image2Click(TObject *Sender)
{
	count++;
    if(count<5){
    	 Image2->Picture= Image10->Picture;
    	img2=1;
	  	Image2->Enabled= false;
        check_winner(1);
	  	play_computer();
    }

  }
//---------------------------------------------------------------------------
void __fastcall TForm1::Image7Click(TObject *Sender)
{
	count++;
    if(count<5){
    Image7->Picture= Image10->Picture;
	img7=1;
	Image7->Enabled= false;
     check_winner(1);
	 play_computer();
    }

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image9Click(TObject *Sender)
{
	count++;
    if(count<5){
    Image9->Picture= Image10->Picture;
	img9=1;
	Image9->Enabled= false;
     check_winner(1);
	 play_computer();
    }

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image4Click(TObject *Sender)
{
	count++;
    if(count<5){
    Image4->Picture= Image10->Picture;
	img4=1;
	Image4->Enabled= false;
    check_winner(1);
 	play_computer();

	}

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image8Click(TObject *Sender)
{
	count++;
    if(count<5){
    Image8->Picture= Image10->Picture;
	img8=1;
	Image8->Enabled= false;
    check_winner(1);
	 play_computer();
    }

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image5Click(TObject *Sender)
{
	count++;
    if(count<5){
        Image5->Picture= Image10->Picture;
    	img5=1;
		Image5->Enabled= false;
        check_winner(1);
        play_computer();
    }

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image3Click(TObject *Sender)
{
	count++;
    if(count<5){
    Image3->Picture= Image10->Picture;
	img3=1;
	Image3->Enabled= false;
    check_winner(1);
 	play_computer();
    }

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image6Click(TObject *Sender)
{
	count++;
    if(count<5){
    Image6->Picture= Image10->Picture;
	img6=1;
	Image6->Enabled= false;
    check_winner(1);
 	play_computer();
    }

}
//---------------------------------------------------------------------------
void play_computer(){
 r=rand()%9+1;
 if (r==1 && Form1->Image1->Enabled==true){
 	Form1->Image1->Picture= Form1->Image11->Picture;
    Form1->Image1->Enabled=false;
    img1=2;
    check_winner(2);
    }
 else if (r==2 && Form1->Image2->Enabled==true){
	Form1->Image2->Picture= Form1->Image11->Picture;
    Form1->Image2->Enabled=false;
    img2=2;
    check_winner(2);
    }
 else if(r==3 && Form1->Image3->Enabled==true){
 	Form1->Image3->Picture= Form1->Image11->Picture;
    Form1->Image3->Enabled=false;
    img3=2;
    check_winner(2);
    }
 else if(r==4 && Form1->Image4->Enabled==true){
 	Form1->Image4->Picture= Form1->Image11->Picture;
    Form1->Image4->Enabled=false;
    img4=2;
    check_winner(2);
    }
 else if(r==5 && Form1->Image5->Enabled==true){
 	Form1->Image5->Picture= Form1->Image11->Picture;
    Form1->Image5->Enabled=false;
    img5=2;
    check_winner(2);
    }
else if(r==6 && Form1->Image6->Enabled==true){
 	Form1->Image6->Picture= Form1->Image11->Picture;
    Form1->Image6->Enabled=false;
    img6=2;
    check_winner(2);
    }
else if(r==7 && Form1->Image7->Enabled==true){
 	Form1->Image7->Picture= Form1->Image11->Picture;
    Form1->Image7->Enabled=false;
    img7=2;
    check_winner(2);
    }
else if(r==8 && Form1->Image8->Enabled==true){
 	Form1->Image8->Picture= Form1->Image11->Picture;
    Form1->Image8->Enabled=false;
    img8=2;
    check_winner(2);
    }
else if(r==9 && Form1->Image9->Enabled==true){
 	Form1->Image9->Picture= Form1->Image11->Picture;
    Form1->Image9->Enabled=false;
    img9=2;
    check_winner(2);
    }
else{
	play_computer();
    }


}
void check_winner(int a){
    String message1;
	if (a==1){
     	message1= "YOU ARE WINNER!!"; }
    else if (a==2){
    	message1="COMPUTER WON!! U LOOSER!!";
        }

	if(img1==a && img2==a && img3==a){

     ShowMessage(message1);
    }
    else if(img1==a && img4==a && img7==a){
     ShowMessage(message1);
    }
    else if(img1==a && img5==a && img9==a){
     ShowMessage(message1);
    }
    else if(img2==a && img5==a && img8==a){
     ShowMessage(message1);
    }
    else if(img3==a && img5==a && img7==a){
    ShowMessage(message1);
    }
    else if(img3==a && img6==a && img9==a){
    ShowMessage(message1);
    }
    else if(img4==a && img5==a && img6==a){
    ShowMessage(message1);
    }
    else if(img7==a && img8==a && img9==a){
    ShowMessage(message1);
    }
    

    

}

void enable_box(){
   Form1->Image1->Enabled=true;
   Form1->Image2->Enabled=true;
   Form1->Image3->Enabled=true;
   Form1->Image4->Enabled=true;
   Form1->Image5->Enabled=true;
   Form1->Image6->Enabled=true;
   Form1->Image7->Enabled=true;
   Form1->Image8->Enabled=true;
   Form1->Image9->Enabled=true;
   Form1->Image1->Picture= Form1->Image12->Picture;
   Form1->Image2->Picture= Form1->Image12->Picture;
   Form1->Image3->Picture= Form1->Image12->Picture;
   Form1->Image4->Picture= Form1->Image12->Picture;
   Form1->Image5->Picture= Form1->Image12->Picture;
   Form1->Image6->Picture= Form1->Image12->Picture;
   Form1->Image7->Picture= Form1->Image12->Picture;
   Form1->Image8->Picture= Form1->Image12->Picture;
   Form1->Image9->Picture= Form1->Image12->Picture;
   img1=0, img2=0,img3=0,img4=0,img5=0,img6=0,img7=0,img8=0,img9=0;
   count=0;
   r=0;
   }
//---------------------------------------------------------------------------

//---------------------------------------------------------------------------
void __fastcall TForm1::Button1Click(TObject *Sender)
{
enable_box();
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button2Click(TObject *Sender)
{
 Form1->Close();	
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button3Click(TObject *Sender)
{
ShowMessage("Bhaskar[@xlinkerz|cipher_x]-|-ParasNath[@opnchaudhary]");	
}
//---------------------------------------------------------------------------