import time

def focus_timer(duration):
    print("专注时间开始！")
    time.sleep(duration)
    print("专注时间结束！")

if __name__ == "__main__":
    duration = int(input("请输入专注时间（以分钟为单位）："))
    duration *= 60  # 转换为秒

    focus_timer(duration)
