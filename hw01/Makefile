# 編譯器與參數
CC = gcc
CFLAGS = -Wall -Wextra -O2

# 檔案與目標名稱
TARGET = hw01
SRC = hw01.c

# 預設目標：編譯
all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC)

# 清除編譯產物
clean:
	rm -f $(TARGET)
