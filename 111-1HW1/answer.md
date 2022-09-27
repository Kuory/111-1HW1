# 第1次作業-作業-HW1
>
>學號：108111121
><br />
>姓名：郭柏葳 
><br />
>作業撰寫時間：30 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/9/27
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容
創建一個test.aspx檔案，再拉出一顆按鈕更改ID， 用Response.Write輸出一段文字


```csharp
p    public partial class test : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            Response.Write("Hello App");
        }

        protected System.Void btn_Show_Click(System.Object sender, System.EventArgs e)
        {
            Response.Write("Hello btn_Show");
        }
    }

若要於內文中標示部分.aspx檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
            <asp:Button ID="btn_Show" runat="server" Text="Button" OnClick="btn_Show_Click" />
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

需要擁有最基礎的程式語言能力，還有最基礎的閱讀題目的國文能力，需要清晰的邏輯架構以及上課認真聽講才能完成作業 
