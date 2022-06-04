unit halamanLogin;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TFHalamanLogin = class(TForm)
    Label1: TLabel;
    Label2: TLabel;
    Label3: TLabel;
    Edit2: TEdit;
    Edit3: TEdit;
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    Edit1: TEdit;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  FHalamanLogin: TFHalamanLogin;

implementation

{$R *.dfm}

procedure TFHalamanLogin.Button1Click(Sender: TObject);
begin
showMessage ('Id:'+edit1.Text+#13#10+
              'Nama:'+edit2.Text+#13#10+
              'fakultas: '+edit3.Text+#13#10)
end;

procedure TFHalamanLogin.Button2Click(Sender: TObject);
begin
edit1.Clear;
edit2.Clear;
edit3.Clear;
end;

procedure TFHalamanLogin.Button3Click(Sender: TObject);
begin
application.Terminate;
end;

end.
