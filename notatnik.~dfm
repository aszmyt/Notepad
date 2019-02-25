object Form1: TForm1
  Left = 1010
  Top = 240
  Width = 486
  Height = 548
  Caption = 'Notepad'
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'MS Sans Serif'
  Font.Style = []
  Menu = MainMenu1
  OldCreateOrder = False
  OnClose = FormClose
  PixelsPerInch = 96
  TextHeight = 13
  object Tresc: TMemo
    Left = 0
    Top = 0
    Width = 470
    Height = 490
    Align = alClient
    ScrollBars = ssHorizontal
    TabOrder = 0
    OnKeyDown = TrescKeyDown
  end
  object MainMenu1: TMainMenu
    Left = 232
    Top = 8
    object Plik1: TMenuItem
      Caption = '&Plik'
      object Nowy1: TMenuItem
        Caption = '&Nowy'
        OnClick = Nowy1Click
      end
      object N1: TMenuItem
        Caption = '-'
      end
      object Otwrz1: TMenuItem
        Caption = '&Otw'#243'rz'
        OnClick = Otwrz1Click
      end
      object Zapisz1: TMenuItem
        Caption = '&Zapisz      Ctrl+S'
        OnClick = Zapisz1Click
      end
      object Zapiszjako1: TMenuItem
        Caption = '&Zapisz jako'
        OnClick = Zapiszjako1Click
      end
      object N2: TMenuItem
        Caption = '-'
      end
      object Exit1: TMenuItem
        Caption = '&Zako'#241'cz'
        OnClick = Exit1Click
      end
    end
    object Edycja1: TMenuItem
      Caption = 'Edycja'
      object WytnijCtrl1: TMenuItem
        Caption = 'W&ytnij      Ctrl+V'
        OnClick = WytnijCtrl1Click
      end
      object KopiujCtrlC1: TMenuItem
        Caption = 'Kop&iuj      Ctrl+C'
        OnClick = KopiujCtrlC1Click
      end
      object WklejCtrlV1: TMenuItem
        Caption = 'W&klej      Ctrl+V'
        OnClick = WklejCtrlV1Click
      end
    end
    object Format1: TMenuItem
      Caption = 'Format'
      object Zawijaniewierszy1: TMenuItem
        Caption = 'Z&awijanie wierszy'
        Checked = True
        OnClick = Zawijaniewierszy1Click
      end
      object Czcionka1: TMenuItem
        Caption = '&Czcionka'
        OnClick = Czcionka1Click
      end
    end
    object P1: TMenuItem
      Caption = 'P&omoc'
      object Informacja1: TMenuItem
        Caption = 'I&nformacja'
        object Oprogramie1: TMenuItem
          Caption = 'O p&rogramie'
          OnClick = Oprogramie1Click
        end
        object Zapraszamnabloga1: TMenuItem
          Caption = 'Zapraszam na mojego Git'#39'aa'
          OnClick = Zapraszamnabloga1Click
        end
      end
    end
  end
  object OpenDialog1: TOpenDialog
    Filter = 'Pliki tekstowe .txt|.*txt|Wszystkie pliki|*.*'
    Left = 272
    Top = 8
  end
  object SaveDialog1: TSaveDialog
    Filter = 'Plik tekstowy .txt|*.txt|Wszystkie pliki|*.*'
    Options = [ofOverwritePrompt, ofHideReadOnly, ofEnableSizing]
    Left = 312
    Top = 8
  end
  object FontDialog1: TFontDialog
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -11
    Font.Name = 'MS Sans Serif'
    Font.Style = []
    MinFontSize = 0
    MaxFontSize = 0
    Left = 344
    Top = 8
  end
end
