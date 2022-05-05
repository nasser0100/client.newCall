# client.newCall
client.newCall(request).execute()) {             String result = response.body().string();             System.out.println("deleteOrder: " + result);         }     }     private static String createJsonData() {         return "{\"id\": 1, \"name\": \"gpcoder\"}";     }
