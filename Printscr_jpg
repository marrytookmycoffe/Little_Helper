using System.Drawing;
using System.Drawing.Imaging;
using System.Windows.Forms;


namespace Application
{
    class Program
    {
        /// <summary>
        /// it take a print screan of main monitor and save it as jpg. It will appere where your exe is.
        /// </summary>
        static void Main()
        {
            Bitmap bitmap = new Bitmap(Screen.PrimaryScreen.Bounds.Width, Screen.PrimaryScreen.Bounds.Height);
            Graphics graphics = Graphics.FromImage(bitmap as Image);
            graphics.CopyFromScreen(0, 0, 0, 0, bitmap.Size);

            bitmap.Save("printcreen.jpg", ImageFormat.Jpeg);
        }
    }
}
