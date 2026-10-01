\# 3. Memory Layout



Một chương trình khi chạy thường có các vùng bộ nhớ chính:



```text

Địa chỉ cao

+----------------+

|     Stack      |

+----------------+

|                |

|      ...       |

|                |

+----------------+

|      Heap      |

+----------------+

|      BSS       |

+----------------+

|      Data      |

+----------------+

|     .rodata    |

+----------------+

|     .text      |

+----------------+

Địa chỉ thấp

