# GitHub Issue & Kanban Writing Guide (Team Beginner-Friendly)

> Mục tiêu: Ai trong team (kể cả chưa có kinh nghiệm) cũng **viết được Issue rõ ràng**, dùng được với **GitHub Projects – Kanban Board**.

---

## 1. Nguyên tắc chung (bắt buộc)

1. **1 Issue = 1 việc**
2. **Viết để người khác đọc là làm được**
3. **Không cần văn hay – chỉ cần rõ**

Issue **không phải báo cáo tiến độ**, cũng **không phải chỗ viết code**.

---

## 2. Cấu trúc Issue chuẩn (dùng cho mọi Issue)

### 2.1. Issue Title

**Công thức**

```
[Type] Verb + What
```

**Type (chỉ dùng các loại sau):**

* Feature
* Bug
* Refactor
* Task

**Verb nên dùng:**

* Implement
* Add
* Update
* Fix
* Refactor

**Ví dụ đúng:**

* `[Feature] Implement login functionality`
* `[Bug] Login fails with correct credentials`
* `[Task] Setup environment variables for auth`

**Ví dụ sai:**

* `Login`
* `Fix auth`
* `Bug login`

---

### 2.2. Issue Description (Template chuẩn)

```md
## What
Nói ngắn gọn việc cần làm.

## Scope
- Gạch đầu dòng những việc chính
- Không quá 5 dòng

## Done when
- Điều kiện để coi là xong
- Có thể test / quan sát được
```

> ⚠️ Không bỏ trống phần **Done when**.

---

## 3. Ví dụ Issue mẫu (copy dùng luôn)

### 3.1. Feature – Login

**Title**

```
[Feature] Implement login functionality
```

**Description**

```md
## What
Allow user to login using email and password.

## Scope
- Receive email and password
- Validate credentials
- Return access token

## Done when
- User can login successfully
- Invalid credentials return error
```

---

### 3.2. Feature – Register

**Title**

```
[Feature] Implement register functionality
```

**Description**

```md
## What
Allow user to create a new account.

## Scope
- Register with email and password
- Validate input data
- Prevent duplicate email

## Done when
- User can register successfully
- Duplicate email is rejected
```

---

### 3.3. Bug

**Title**

```
[Bug] Login fails with correct credentials
```

**Description**

```md
## What
User cannot login even with correct email and password.

## Scope
- Check authentication logic
- Fix login error

## Done when
- User can login with correct credentials
```

---

### 3.4. Task

**Title**

```
[Task] Setup environment variables for authentication
```

**Description**

```md
## What
Setup environment variables for authentication module.

## Scope
- Add env configuration
- Update documentation

## Done when
- Application runs without missing env errors
```

---

## 4. Quy ước Kanban Board (GitHub Projects)

### 4.1. Các cột chuẩn

```
Backlog | Todo | In Progress | Review | Done
```

**Ý nghĩa:**

* **Backlog**: việc chưa cần làm ngay
* **Todo**: việc đã rõ, sẵn sàng làm
* **In Progress**: đang code
* **Review**: đã mở Pull Request
* **Done**: PR đã merge

---

### 4.2. Luồng làm việc chuẩn

```
Create Issue
→ Todo
→ In Progress (tạo branch)
→ Review (mở PR)
→ Done (merge PR)
```

---

## 5. Quy ước Pull Request

### 5.1. PR phải gắn Issue

Trong PR description:

```md
Fixes #<issue-id>
```

**Khi merge PR:**

* Issue tự động đóng
* Task tự chuyển sang Done

---

## 6. Rule cho toàn team (bắt buộc tuân theo)

1. ❌ Không tạo Issue chỉ có title
2. ❌ Không gộp nhiều việc vào 1 Issue
3. ❌ Không kéo task sang Done nếu chưa merge PR
4. ✅ Mỗi PR phải liên kết ít nhất 1 Issue
5. ✅ Dùng đúng template Issue

---

## 7. Câu chốt cho team (dán vào README)

> **Issue không cần hay – chỉ cần rõ. Người khác đọc là làm được.**

---

## 8. Gợi ý cấu trúc thư mục

```
.github/
  ISSUE_TEMPLATE.md
README.md
```

Bạn có thể copy **Template Issue** ở trên vào `.github/ISSUE_TEMPLATE.md` để GitHub tự động áp dụng khi tạo Issue mới.
