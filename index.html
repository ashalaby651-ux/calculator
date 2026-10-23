import tkinter as tk
from tkinter import font

class ElKazzazCalculator:
    def __init__(self, root):
        self.root = root
        self.root.title("الآلة الحاسبة - مكتب القزاز للبرمجيات")
        self.root.geometry("350x500")
        self.root.resizable(False, False)
        self.root.configure(bg="#0f172a")

        self.expression = ""
        self.input_text = tk.StringVar()

        # إطار الشاشة (Display)
        display_frame = tk.Frame(self.root, bg="#0f172a", height=100)
        display_frame.pack(pack_propagate=False, fill=tk.BOTH)

        # شاشة عرض الأرقام والعمليات
        custom_font = font.Font(family="Tahoma", size=24, weight="bold")
        input_field = tk.Entry(display_frame, textvariable=self.input_text, font=custom_font, 
                               bg="#1e293b", fg="#ffffff", bd=0, justify=tk.RIGHT)
        input_field.pack(fill=tk.BOTH, expand=True, padx=15, pady=15)

        # إطار الأزرار
        buttons_frame = tk.Frame(self.root, bg="#0f172a")
        buttons_frame.pack(fill=tk.BOTH, expand=True, padx=10, pady=10)

        # تصميم الأزرار
        buttons = [
            ('C', 1, 0, "#ef4444"), ('⌫', 1, 1, "#64748b"), ('%', 1, 2, "#64748b"), ('/', 1, 3, "#f59e0b"),
            ('7', 2, 0, "#334155"), ('8', 2, 1, "#334155"), ('9', 2, 2, "#334155"), ('*', 2, 3, "#f59e0b"),
            ('4', 3, 0, "#334155"), ('5', 3, 1, "#334155"), ('6', 3, 2, "#334155"), ('-', 3, 3, "#f59e0b"),
            ('1', 4, 0, "#334155"), ('2', 4, 1, "#334155"), ('3', 4, 2, "#334155"), ('+', 4, 3, "#f59e0b"),
            ('0', 5, 0, "#334155"), ('.', 5, 1, "#334155"), ('=', 5, 2, 2, "#2563eb")
        ]

        for btn in buttons:
            text = btn[0]
            row = btn[1]
            col = btn[2]
            bg_color = btn[3]
            colspan = btn[4] if len(btn) > 4 else 1

            button = tk.Button(buttons_frame, text=text, font=("Tahoma", 16, "bold"),
                               fg="#ffffff", bg=bg_color, bd=0, activebackground="#475569",
                               command=lambda t=text: self.on_button_click(t))
            
            button.grid(row=row, column=col, columnspan=colspan, sticky="nsew", padx=4, pady=4)

        for i in range(4):
            buttons_frame.columnconfigure(i, weight=1)
        for i in range(6):
            buttons_frame.rowconfigure(i, weight=1)

    def on_button_click(self, char):
        if char == 'C':
            self.expression = ""
            self.input_text.set("")
        elif char == '⌫':
            self.expression = self.expression[:-1]
            self.input_text.set(self.expression)
        elif char == '=':
            try:
                result = str(eval(self.expression))
                self.input_text.set(result)
                self.expression = result
            except Exception:
                self.input_text.set("خطأ")
                self.expression = ""
        else:
            self.expression += str(char)
            self.input_text.set(self.expression)

if __name__ == "__main__":
    root = tk.Tk()
    app = ElKazzazCalculator(root)
    root.mainloop()
